<template>
    <h1>Simple Form</h1>
    <ul>
        <li v-for="item in error" v-bind:key="item">
        {{ item }} not valid</li>
    </ul>
    <form>
        <label>Email: </label>
        <input type="email" placeholder="Enter Email" v-model="form.email"/>
        <br/> <br/>

        <label>Password: </label>
        <input type="password" placeholder="Enter Password" v-model="form.password"/>
        <br/> <br/>

        <button type="button" @click="login()">Login</button>
    </form>

</template>

<script>
import ParentToChild from './parentToChild.vue'

    export default {
        name: "simpleForm",
        data() {
            return {
                form: {
                    email: '',
                    password: ''
                },
                error: []
            }
        },
        methods: {
            login(){
                this.error=[];
                for(const item in this.form){
                    if(this.form[item]==="" || this.form[item].length===0){
                        this.error.push(item)
                    }
                }
                if(this.error.length===0){
                    alert("data has been submitted")
                }
                // document.write("Email: ", this.form.email)
                // document.write("Password: ", this.form.password)
                // console.log(this.error)
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>