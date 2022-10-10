<template>
  <div>
    <nav-bar msg="this is NavBar">
      <template #headline>
        <icon-comp />
        <h1>Head Line</h1>
      </template>

      <template #content>
        <p>content</p>
      </template>
    </nav-bar>
  </div>
</template>

<script>
import NavBar from "./components/NavBar/nav-bar.vue";
import iconComp from "./components/icons/icon-comp.vue";

export default {
  name: "App",
  components: {
    NavBar,
    iconComp,
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
