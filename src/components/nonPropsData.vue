<template>
    <h1>Non props data</h1>
    <NonPropUser data="some data" id="user-cmp"/>
</template>

<script>
import NonPropUser from './nonPropUser.vue';

    export default {
    name: "nonPropsData",
    components: { NonPropUser }
}
</script>

<style lang="scss" scoped>

</style>