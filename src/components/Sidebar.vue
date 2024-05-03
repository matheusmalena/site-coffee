<template>
  <div class="w-25 d-flex flex-column align-items-center gap-3 justify-content-end">
    <a href="" class="links-menu">Inicio</a>
    <a href="" class="links-menu">Sobre</a>
    <a href="" class="links-menu">Cardápio</a>
    <a href="" class="links-menu">News</a>
    <a href="" class="links-menu">Sobre nós</a>
  </div>
</template>

<!-- eslint-disable-next-line -->
<script>
export default {
    // eslint-disable-next-line vue/multi-word-component-names
    name: 'Sidebar',
};
</script>

<style scoped>
/* Estilos para o sidebar */
.sidebar {
  width: 250px;
  height: 100%;
  background-color: #333;
  padding-top: 20px;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  padding: 10px;
}

a {
  color: #fff;
  text-decoration: none;
  font-size: 18px;
}

a:hover {
  color: #ccc;
}
</style>
