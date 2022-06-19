<template>
    <div class="bg-gray-800 h-screen text-white">
        <div class="p-10 text-center">
            <Bars></Bars>
            <Navigation></Navigation>
        </div>
    </div>
</template>

<script>
import Bars from "@/components/bars.vue";
import Navigation from "@/components/navigation.vue";


export default {
    name: "Home",
    components: {
        Navigation,
        Bars
    },
}

</script>