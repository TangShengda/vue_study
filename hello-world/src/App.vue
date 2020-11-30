<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />

    <div id="app-7">

      <ClassStyle></ClassStyle>
    </div>
  </div>
</template>

<script>

import ClassStyle from "./components/ClassStyle";
export default {
  name: "App",
  data() {
    return {
      message: "你很厉害",
    };
  },

  components: {
    ClassStyle
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
