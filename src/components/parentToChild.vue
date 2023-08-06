<template>
    <h1>Parent Component</h1>
    <childComponent name="Zain" :user="user" :getData="getData"/>
</template>

<script>
import childComponent from './childComponent.vue';

    export default {
        name: "parentToChild",
        components:{
            childComponent
        },
        data(){
            return{
                user:{name: "zain", email:"zain@gmsil.com"}
            }
        },
        methods:{
            getData(){
                alert("Parent function called")
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>