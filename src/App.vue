<template>
  <app-header />
  <router-view />
</template>

<script>
// @ is an alias to /src
import AppHeader from "@/components/AppHeader.vue";

export default {
  name: "App",
  components: {
    AppHeader,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
