<template>
    <h1>Events</h1>
    <button @click="increement()">Increement</button>
    <button @click="decreement()">Decreement</button>
    <h1>Count= {{ count }}</h1>
</template>

<script>
export default {
    name: "Event",
    data() {
        return {
            count: 0
        }
    },
    methods: {
        increement() {
            this.count++
        },
        decreement() {
            this.count--
        }
    }
}
</script>

<style scoped>

</style>