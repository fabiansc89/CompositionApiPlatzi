
<template>
  <Home first-name="Fabian Gabriel" last-name="Soto Canales"></Home>
</template>

<script>
import Home from "@/components/Home.vue";
import { provide } from "vue";
export default {
  name: "App",
  components: {
    Home,
  },
  setup() {
    provide("username", "Fabito");
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