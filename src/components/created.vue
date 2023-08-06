<template>
    <h1>beforeCreated and Created {{ name }}</h1>
</template>

<script>
    export default {
        name: "Created",
        data(){
            alert(" data created")
            return{
                name: "zain"
            }
        },
        beforeCreate(){
            alert("beforeCreated")
        },
        created(){
            this.name="akram"
            alert("created")
        }
    }
</script>

<style lang="scss" scoped>

</style>