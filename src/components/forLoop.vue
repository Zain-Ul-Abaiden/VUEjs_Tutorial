<template>
    <h1>for loop</h1>
    <ul>
        <li v-for="item in technology" :key="item">
            {{ item }}
        </li>
    </ul>
    <br/>
    <ul>
        <li v-for="(x,item) in user" :key="item">
            User {{item+1}} Name is: {{ x.name }} and email is: {{ x.email }}
        </li>
    </ul>
    <br/>
</template>

<script>
    export default {
        name: "forLoop",
        data(){
            return {
                technology: ['java', 'php', 'node', 'html'],
                user:[
                    {name: "zain", email: "zain@gmail.com"},
                    {name: "waseem", email: "waseem@gmail.com"}
                ]
            }
        }
    }
</script>

<style scoped>

</style>