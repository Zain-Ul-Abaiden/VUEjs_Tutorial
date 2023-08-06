<template>
    <h1 v-if="show">If condition</h1>
    <h1 v-else>Else condition</h1>
    <button @click="show=!show">Toogle</button>
</template>

<script>
    export default {
        name: "canditionalRendring",
        data() {
            return {
                show:true
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>