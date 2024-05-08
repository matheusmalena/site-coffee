<template>
  <main>
    <ExplorerProduts />
    <Favorite/>
  </main>
</template>

<script>
import ExplorerProduts from "@/components/ExplorerProduts.vue";
import Favorite from './Favorite.vue';

export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Main",
  components: {
    ExplorerProduts,
    Favorite,
  },
};
</script>

<style scoped>
h1 {
  font-family: var(--font-alkalami);
  font-size: 40px;
}
</style>
