<template>
  <div id="app">
    <app-header></app-header>
    <!-- :key="$route.path" -->
    <router-view />
    <app-footer></app-footer>
  </div>
</template>
<script>
import AppHeader from "./layout/AppHeader.vue";
import AppFooter from "./layout/AppFooter.vue";
export default {
  name: "App",
  components: {
    AppHeader,
    AppFooter,
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
}
</style>
