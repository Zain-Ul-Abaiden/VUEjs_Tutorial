<template>
    <h1>Computed Properties</h1>
    <h2>{{ getResult }}</h2>
</template>

<script>
    export default {
        name: "computed",
        data(){
            return {
                dollors: 100,
                rupeeVal: 70,
                discount: 10
            }
        },
        computed:{
            getResult(){
                return (this.dollors*this.rupeeVal) - this.discount
            }
        }
    }
</script>

<style scoped>

</style>