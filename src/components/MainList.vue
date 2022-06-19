<template>
  <ul class="mail-list">
    <ListItem />
  </ul>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import ListItem from "@/components/ListItem.vue";

export default defineComponent({
  name: "MainList.vue",
  components: {
    ListItem,
  },
});
</script>

<style scoped></style>
