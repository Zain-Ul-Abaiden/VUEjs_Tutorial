<template>
    <h2>Child component to parent component</h2>
    <button @click="getUser(userName)">Send User Name</button>
</template>

<script>
    export default {
        name: "childToParent",
        data(){
            return{
                userName:"Zain"
            }
        },
        props:{
            getUser: Function
        }
    }
</script>

<style lang="scss" scoped>

</style>