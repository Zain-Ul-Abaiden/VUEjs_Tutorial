<template>
    <h1>Parent component {{ childUser }}</h1>
    <childToParent :getUser="getUserName"/>
</template>


<script>
import childToParent from './childToParent.vue';
    export default {
        name: "parentComponent",
        components:{
            childToParent
        },
        data(){
            return {
                childUser:""
            }
        },
        methods: {
            getUserName(name){
                this.childUser=name
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>