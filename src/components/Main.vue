<template>
  <main>
    <ExplorerProduts />
  </main>
</template>

<script>
import ExplorerProduts from "@/components/ExplorerProduts.vue";

export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Main",
  components: {
    ExplorerProduts,
  },
};
</script>

<style scoped>
h1 {
  font-family: var(--font-alkalami);
  font-size: 40px;
}
</style>
