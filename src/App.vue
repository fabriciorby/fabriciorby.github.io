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
  background-image: url("./assets/spaceBG2.gif");
}
html {
  height: 100%;
  cursor: url("./assets/cursor.gif"), auto;
}
a {
  cursor: url("./assets/cursor.gif"), auto;
}
#app {
  font-family: "Roboto Mono", monospace;
  text-align: center;
}
</style>
