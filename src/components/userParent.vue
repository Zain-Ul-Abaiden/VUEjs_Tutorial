<template>
    <h1>User Parent Component Reuse</h1>
    <ul>
        <li v-for="item in users" :key="item">
            <userChild :data="item" :getData="getData"/>
        </li>
        
    </ul>
</template>

<script>
import userChild from './userChild.vue';

    export default {
    name: "userParent",
    components: { userChild },
    data(){
        return{
            users:[
                {name:'zain', email:'zain@gmail.com'},
                {name:'waseem', email:'waseem@gmail.com'},
                {name:'junaid', email:'junaid@gmail.com'},
                {name:'jamshed', email:'jamshed@gmail.com'},
            ]
        }
    },
    methods:{
        getData(){
            alert("hello")
        }
    }
}
</script>

<style lang="scss" scoped>

</style>