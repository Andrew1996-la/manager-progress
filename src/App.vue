<template>
  <div id="app">
    <HeaderApp />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HeaderApp from "@/components/HeaderApp.vue";

export default defineComponent({
  name: "App",
  components: {
    HeaderApp,
  },
});
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
