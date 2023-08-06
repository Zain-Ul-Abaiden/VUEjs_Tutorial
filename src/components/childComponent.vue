<template>
    <h2>Child Component</h2>
    Name from Parent component is {{ name }}
    <br/>
    User data from Parent component is {{ user }}
    <br/>
    <button type="button" @click="getData()">Call function</button>
</template>

<script>
    export default {
        name: "childComponent",
        props: {
            name: String,
            user: Object,
            getData: Function
        },
    }
</script>

<style lang="scss" scoped>

</style>