<template>
    <h1>beforeupdate and updated</h1>
    <h2>{{ counter }}</h2>
    <button @click="counter=counter+1">Update Count</button>
</template>

<script>
    export default {
        name: "Update",
        data(){
            alert("data part")
            return{
                counter:0
            }
        },
        beforeUpdate(){
            alert("beforeupdtae")
        },
        updated(){
            alert("updated")
        }
    }
</script>

<style lang="scss" scoped>

</style>