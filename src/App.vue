<template>
  <div id="app">
    <HelloWorld msg="Classic Cheesecake Recipe" />
    <img class="cheesecake" alt="cheesecake" src="./assets/photo1.png" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
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
