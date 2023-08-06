<template>
    <h1>HTML Biding</h1>
    <h1 >{{ name }}</h1>
    <div v-html="tag">
    </div>
</template>

<script>
    export default {
        name: "htmlBiding",
        data(){
            return{
                name: "Zain",
                tag: "<h1>Akram</h1>"
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>