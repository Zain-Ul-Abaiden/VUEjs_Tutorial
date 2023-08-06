<template>
    <h1>Get Input Value</h1>
    <input type="text" placeholder="Enter email here" v-model="email"/>
    <br />
    <br />
    <input type="password" placeholder="Enter password here" v-model="password"/>
    <br />
    <br />
    <button type="button" @click="getData()">Get Value</button>
</template>

<script>
    export default {
        name: "getInput",
        data() {
            return {
                email: null,
                password: null
            }
        },
        methods: {
            getData() {
                document.write("Email: ", this.email)
                
                document.write("Password: ", this.password)
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>