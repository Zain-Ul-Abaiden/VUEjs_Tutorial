<template>
    <h1>Get Checkbox & Radio Button value</h1>
    <h3>Technology</h3>
    <label for="java">Java</label>
    <input type="checkbox" value="java" v-model="technology" id="java">
    <br/>
    <label for="php">Php</label>
    <input type="checkbox" value="php" v-model="technology" id="php">
    <br/>
    <label for="node">Node</label>
    <input type="checkbox" value="node" v-model="technology" id="node">
    <br/>
    <h3>Who I am</h3>
    <label for="student">Student</label>
    <input type="radio" value="student" name="who" v-model="who" id="student">
    <br/>
    <label for="developer">Developer</label>
    <input type="radio" value="developer" name="who" v-model="who" id="developer">
    <br/>
    <h4>Selected Technology: {{ technology }}</h4>
    <h4>Wwho I am a {{ who }}</h4>
</template>

<script>
    export default {
        name: "getButtonValue",
        data() {
            return {
                technology: [],
                who: null,
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>