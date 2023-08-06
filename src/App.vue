<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <HelloWorld msg="Welcome to Your Vue.js App" />
  <!-- <Home /> -->
  <!-- <Event /> -->
  <!-- <twowaybiding /> -->
  <!-- <GetInput /> -->
  <!-- <GetButtonValue /> -->
  <!-- <CanditionalRendring /> -->
  <!-- <forLoop /> -->
  <!-- <ParentToChild /> -->
  <!-- <UserParent /> -->
  <!-- <HtmlBiding /> -->
  <!-- <parentComponent /> -->
  <!-- <ref /> -->
  <!-- <simpleForm /> -->
  <!-- <modifiers /> -->
  <!-- <nonPropsData /> -->
  <!-- <computed /> -->
  <!-- <watchers /> -->
  <!-- <Created /> -->
  <!-- <Mount /> -->
  <Update />
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Home from "./components/Home.vue";
import Event from "./components/Event.vue";
import twowaybiding from "./components/twowaybiding.vue";
import GetInput from "./components/getInput.vue";
import GetButtonValue from "./components/getButtonValue.vue";
import CanditionalRendring from "./components/canditionalRendring.vue";
import forLoop from "./components/forLoop.vue";
import ParentToChild from "./components/parentToChild.vue";
import UserParent from "./components/userParent.vue";
import HtmlBiding from "./components/htmlBiding.vue";
import parentComponent from "./components/parentComponent.vue";
import ref from "./components/ref.vue";
import simpleForm from "./components/simpleForm.vue";
import modifiers from "./components/modifiers.vue";
import nonPropsData from "./components/nonPropsData.vue";
import computed from "./components/computed.vue";
import watchers from "./components/watchers.vue";
import Created from "./components/created.vue";
import Mount from "./components/mount.vue";
import Update from "./components/update.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    Home,
    Event,
    twowaybiding,
    GetInput,
    GetButtonValue,
    CanditionalRendring,
    forLoop,
    ParentToChild,
    UserParent,
    HtmlBiding,
    parentComponent,
    ref,
    simpleForm,
    modifiers,
    nonPropsData,
    computed,
    watchers,
    Created,
    Mount,
    Update
},
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
