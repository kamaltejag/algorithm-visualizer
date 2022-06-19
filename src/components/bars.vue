<template>
    <div class="grid grid-flow-col auto-cols-max gap-1 rotate-180">
        <Bar v-for="bar of bars" :bar="bar"></Bar>
    </div>
</template>

<script>
import Bar from "@/components/bar.vue";
export default {
    name: "Bars",
    components: {
        Bar
    },
    data() {
        return {
            bars: []
        }
    },
    mounted: function () {
        return this.generateBars()
    },
    methods: {
        getWidth() {
            if (self.innerWidth) {
                return self.innerWidth;
            }

            if (document.documentElement && document.documentElement.clientWidth) {
                return document.documentElement.clientWidth;
            }

            if (document.body) {
                return document.body.clientWidth;
            }
        },
        getHeight() {
            if (self.innerHeight) {
                return self.innerHeight;
            }

            if (document.documentElement && document.documentElement.clientHeight) {
                return document.documentElement.clientHeight;
            }

            if (document.body) {
                return document.body.clientHeight;
            }
        },
        generateBars() {
            let width = this.getWidth();
            let height = this.getHeight();

            let maxBars = Math.round(width / 7) - 70;
            let maxBarHeight = height - 260;

            for (let i = 0; i < maxBars; i++) {
                let num = Math.floor((Math.random() * maxBarHeight) + 1);
                this.bars.push(num);
            }
        }

    }
}
</script>