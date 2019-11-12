<template>
  <div id="app">
    <Header></Header>
    <router-view />
  </div>
</template>

<script>
import Header from "@/components/Header";
export default {
  components: {
    Header
  }
};
</script>

<style>
@import url("https://fonts.googleapis.com/css?family=Open+Sans:300,400,600,700,800");

#app {
  font-family: "Open Sans", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;

  position: absolute;
  width: 100%;
  height: 100%;
  left: 0;
  top: 0;
}
</style>
