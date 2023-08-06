<template>
    <h1>Form Modifiers</h1>
    <input type="text" v-model.lazy="data" />
    <h2>Data is: {{ data }}</h2>
    <!-- <input type="text" v-model.lazy="data" />
    <input type="number" v-model.number="data" /> -->
</template>

<script>
    export default {
        name: "modifiers",
        data() {
            return {
                data: ''
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>