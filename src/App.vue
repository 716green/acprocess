<template>
  <div class="app">
    <div class="header">
      <img class="image" src="./assets/acpLogo.png" />
      <div class="title">AC Processing</div>
    </div>
    <Main />
  </div>
</template>

<script>
import Main from "./components/Main.vue";

export default {
  name: "App",
  components: {
    Main,
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
* {
  font-family: Verdana, Geneva, Tahoma, sans-serif;
}
body {
  padding: 20px 100px;
  background-color: rgba(128, 128, 128, 0.253);
}
.title {
  font-size: 3.4rem;
  margin: auto;
}
.image {
  width: 80px;
  position: relative;
}
.header {
  display: flex;
  margin: auto;
}
</style>
