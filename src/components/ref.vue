<template>
    <h1>Ref in VUE</h1>
    <input type="text" ref="input" />
    <button @click="getData()">Click Me</button>
</template>

<script>
    export default {
        name: "ref",
        methods:{
            getData(){
                this.$refs.input.focus();
                let val=this.$refs.input.value;
                console.log(val);
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>