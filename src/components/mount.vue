<template>
    <h1>beforemount and mounted {{ name }}</h1>
</template>

<script>
    export default {
        name: "Mount",
        data(){
            alert("data part")
            return{
                name: 'zain'
            }
        },
        beforeMount(){
            alert("beforemount")
        },
        mounted(){
            alert("mounted")
        }
    }
</script>

<style lang="scss" scoped>

</style>