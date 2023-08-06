<template>
    <h1>Two way biding</h1>
    <input type="text" v-model="count"/>
    <h2>{{ count }}</h2>
</template>

<script>
    export default {
        name: "twowaybiding",
        data() {
            return {
                count: 0
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>