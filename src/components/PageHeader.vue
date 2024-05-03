<template>
  <section class="cabecalho d-flex justify=content-between align-items-center">
    <div class="w-25">
      <img
        src="https://divinoparis.com.br/wp-content/uploads/2023/08/SITE-37.png"
        alt=""
      />
      <h1>Coffee</h1>
    </div>
    <div class="w-75 d-flex align-items-center gap-3 justify-content-end">
      <div class="sidebar">
        <a href="" class="links-menu">Inicio</a>
        <a href="" class="links-menu">Sobre</a>
        <a href="" class="links-menu">Cardápio</a>
        <a href="" class="links-menu">News</a>
        <a href="" class="links-menu">Sobre nós</a>
      </div>
      <span class="material-symbols-outlined personalize-i"> shopping_bag </span>
        <button class="button-buy">Comprar tickets</button>
    </div>
    <!-- Ícone do menu para telas menores de 960px -->
    <div class="menu-icon d-flex align-items-center justify-content-center">
      <button class="menu-btn menu-icon" onclick="toggleMenu()">
        <span class="material-symbols-outlined"> menu </span>
      </button>
    </div>
  </section>
</template>

<script>
export default {
  name: "PageHeader",
  props: {
    msg: String,
  },
  methods: {
    toggleMenu() {
      
    },
  },
};
</script>

<style scoped>
* {
  text-decoration: none;
}

.cabecalho {
  background-color: var(--bg-secudary);
  color: #1b1b1d;
  font-family: "Poppins", sans-serif;
  font-weight: 400;
  padding: 18px;
  margin-top: -25px;
  padding-right: 50px;
}

img {
  width: 8%;
  height: 5%;
  color: #1b1b1d;
}

.links-menu {
  color: var(--color-primary);
  text-decoration: none;
  cursor: pointer;
  font-size: 12px;
  padding: 12px;
  font-weight: 500;
}

.button-buy {
  background-color: var(--color-primary);
  color: var(--white);
  border-radius: 30px;
  padding: 15px;
  border: 1px solid var(--color-primary);
  font-size: 12px;
  cursor: pointer;
}

.personalize-i {
  background-color: var(--white);
  border-radius: 30px;
  padding: 8px;
  font-weight: 600;
  font-size: 22px;
  border: 1px solid var(--white);
  cursor: pointer;
}

.menu-icon {
  display: none;
  border: none;
}

.sidebar {
  display: block;
}

.sidebar.active {
  display: block;
}

@media screen and (max-width: 960px) {
  .menu-icon {
    display: block;
  }

  .sidebar {
    display: none;
  }
}
</style>
