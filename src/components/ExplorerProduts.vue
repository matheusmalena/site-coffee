<template>
  <main class="m-5">
    <div>
      <h1>Explore Our Alowishus</h1>
      <p>
        A drink from the 'My Divina' bootle brews range OR grap one of our delicious
        coffee´s
      </p>
    </div>
    <div class="d-flex gap-3 justify-content-center">
      <div class="card">
        <h2>Our Catering</h2>
        <p>Divina Catering, delicious drop off Catering.</p>
        <span class="material-symbols-outlined icon"> fastfood </span>
        <button class="botao-card">ORDER CATHERING</button>
      </div>

      <div class="card">
        <h2>The Food</h2>
        <p>Our entire menu is available as dine in or takeway.</p>
        <span class="material-symbols-outlined icon"> restaurant </span>
        <button class="botao-card">FOOD MENU</button>
      </div>

      <div class="card">
        <h2>The Gelato</h2>
        <p>Life is like GELATO, enjoy it before it melts.</p>
        <span class="material-symbols-outlined icon"> icecream </span>
        <button class="botao-card">DISCOVER MORE</button>
      </div>
    </div>
  </main>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "ExplorerProduts",
};
</script>

<style SCOPED>
h1 {
  font-family: var(--font-alkalami);
  font-size: 40px;
}

h2{
  font-family: var(--font-alkalami);
  display: flex;
  justify-content: start;
  text-align: left;
  width: 100%;
  padding: 1rem;

}

.icon {
  font-weight: 600 !important;
  font-size: 4rem !important;
  color: var(--cinza) !important;
  padding: 8px;
  margin-bottom: 10px;
}

.botao-card {
  width: 10rem;
  height: 3rem;
  font-size: 10px;
  border: 1px solid var(--color-primary);
  border-radius: 25px;
  padding: 15px;
  text-align: center;
  font-weight: 600;
}

.card {
  width: 32%;
  height: 80%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 1rem;
  padding: 1rem;
}
</style>
