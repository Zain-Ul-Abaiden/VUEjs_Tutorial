<template>
    <h1>Watchers</h1>
    <button @click="count=count+1"> + </button>
    <button @click="count=count-1"> - </button>
    <h2>{{ count }}</h2>
</template>

<script>
    export default {
        name: "watchers",
        data(){
            return{
                count: 0
            }
        },
        watch:{
            count(val,prev){
                if(val>5 && val>prev){
                    alert("Stop counting")
                }
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>