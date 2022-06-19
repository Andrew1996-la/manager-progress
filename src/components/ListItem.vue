<template>
  <li class="list-item"></li>
</template>

<script lang="ts">
import { defineComponent } from "vue";
export default defineComponent({
  name: "ListItem",
});
</script>

<style scoped>
.list-item {
  max-width: 1200px;
  min-height: 500px;
  border: 1px solid black;
  border-radius: 13px;
  list-style-type: none;
}
</style>
