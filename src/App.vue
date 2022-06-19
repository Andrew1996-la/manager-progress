<template>
  <div id="app">
    <HeaderApp />
    <MainList />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HeaderApp from "@/components/HeaderApp.vue";
import MainList from "@/components/MainList.vue";

export default defineComponent({
  name: "App",
  components: {
    HeaderApp,
    MainList,
  },
});
</script>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  width: 1200px;
  margin: 60px auto 0 auto;
}
</style>
