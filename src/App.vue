<template>
  <div id="app">
    <HelloWorld msg="Classic Cheesecake Recipe" />
    <img class="cheesecake" alt="cheesecake" src="./assets/photo1.png" />
    <Instruction></Instruction>
    <Icon></Icon>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Instruction from "./components/Instruction.vue";
import Icon from "./components/Icon.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    Instruction,
    Icon
  },
};
</script>

<style>
.cheesecake{
position: absolute;
width: 969px;
height: 470px;
left: 234px;
top: 193px;
border-radius: 12px;
}


</style>
