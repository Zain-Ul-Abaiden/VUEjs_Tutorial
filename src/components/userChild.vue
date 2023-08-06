<template>
    <div>
        <!-- <h2>User Child Component</h2> -->
        Name: {{data.name}} <br/>
        Email: {{data.email}} <br/>
        <button type="button" @click="getData()">Alert Hello</button>
    </div>
</template>

<script>
    export default {
    name: "userChild",
    props: {
        data : Object,
        getData: Function
    }
}
</script>

<style lang="scss" scoped>

</style>