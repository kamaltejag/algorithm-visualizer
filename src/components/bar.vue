<template>

    <div :style="{
        width: '5px', height: bar + 'px'
    }" class="bg-white "></div>
</template>

<script>
export default {
    name: "Bar",
    props: ["bar"],
}
</script>