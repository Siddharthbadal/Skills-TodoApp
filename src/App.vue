<template>
  <div id="app">
    <skills />
  </div>
</template>

<script>
import skills from "./components/skills.vue";

export default {
  name: "App",
  components: {
    skills
  }
};
</script>




<style>
@import url("https://fonts.googleapis.com/css?family=Montserrat:400,700");

body {
  background-color: #eeeeee;
  font-family: "Montserrat", sans-serif;
  display: grid;
  grid-template-rows: auto;
  justify-items: center;
  align-items: center;
}
body,
html {
  margin: 0;
  height: 100%;
}
#app {
  width: 50%;
}
</style>
