<template>
    <div>
        <h2>Zain</h2>
        <h2>Waseem</h2>
        <h2>Akram</h2>
        <h2 v-bind="$attrs">Zain AKram</h2>
    </div>

</template>

<script>
    export default {
        name: "nonPropUser",
        inheritAttrs: false,
        // props:{
        //     id: String,
        //     data: String
        // }
    }
</script>

<style lang="scss" scoped>

</style>