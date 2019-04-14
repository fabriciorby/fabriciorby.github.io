<template>
  <div id="app">
    <div class="layout">
      <Content/>
    </div>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Menu from "./components/Menu.vue";
import Content from "./components/Content.vue";

export default {
  name: "app",
  components: {
    HelloWorld,
    Menu,
    Content
  }
};
</script>

<style>
body {
  height: 100%;
  padding: 0;
  margin: 0;
}
html {
  height: 100%;
  cursor: url("./assets/cursor.gif"), auto;
}
a {
  cursor: url("./assets/cursor.gif"), auto;
}
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  background-image: url("./assets/spaceBG2.gif");
  height: 100%;
}
</style>
