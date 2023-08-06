<template>
    <h1>Home Component</h1>
    <h1>Email: {{ email }}</h1>
    <h1>Number: {{ mobile }}</h1>
    <h1>Name: {{ getName("Ali") }}</h1>
    <h1>All data: {{ getData().email }}</h1>
</template>

<script>
export default {
    name: 'Home',
    data() {
        return {
            email: "zain@gmail.com",
            mobile: 222,
        }
    },
    methods: {
        getName(ali) {
                return `zain ${ali}`
            },
        getData() {
            return {
                name: 'waseem',
                email: this.email
            }
        }
    }
}
</script>
<style>

</style>