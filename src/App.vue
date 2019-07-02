<template>
  <div id="app">
    <HelloWorld/>
    <EarthImage/>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import EarthImage from "./components/EarthImage";

export default {
  name: "App",
  components: {
    HelloWorld,
    EarthImage
  }
};
</script>

<style>
</style>
