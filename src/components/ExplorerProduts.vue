<template>
  <main class="d-flex flex-column mt-5">
    <div class="d-flex flex-row w-100 justify-content-between ">
      <div class="copo-metade d-flex justify-content-start  "> 
        <img
          class=""
          src="https://i.postimg.cc/N0p8Btgc/Captura-de-tela-2024-05-08-100054-removebg-preview-removebg-preview.png"
          alt=""
        />
      </div>
      <div class="d-flex flex-column first-card align-items-center justify-content-center ">
        <h1>Explore Our Alowishus</h1>
        <p>
          A drink from the 'My Divina' bootle brews range OR grap one of our delicious
          coffee´s
        </p>
      </div>
    </div>

    <div class="d-flex gap-5 justify-content-center cards-card">
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

<style scoped>
h1 {
  font-family: var(--font-alkalami);
  font-size: 40px;
}

main {
  background: linear-gradient(
    0deg,
    rgba(238, 239, 241, 1) 0%,
    rgba(255, 255, 255, 1) 100%
  );
}

h2 {
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
  width: 25%;
  border: 1px solid black;
  border-radius: 20px !important;
  height: 80%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 1rem;
  padding: 1rem;
}

.copo-metade {
  display: flex;
  justify-content: flex-start;
  width: 10%;
  height: auto;
  margin-top: 150px;
}

.copo-metade img {
  width: 200px;
  height: auto;
  margin-bottom: -185px;
}

.first-card{
  margin-top: 120px;
  margin-right: 32%;
}

.cards-card{
  margin-bottom: 250px;
}

@media screen and (max-width: 960px) {
  .card h2 {
    font-size: 18px;
    padding: 0;
    margin: 0;
  }

  .card p {
    font-size: 12px;
  }

  .card {
    padding: 1rem 6px;
  }

  .botao-card {
    width: 100%;
    height: 38px;
    font-size: 8px;
    padding: 5px;
    border-radius: 25px;
  }

  .icon {
    font-size: 40px !important;
  }

  .cards-card{
  margin-top: 40%;
  margin-bottom: 150px;
  gap: 1rem !important;
}

div img{
  width: 120px !important;
  height: auto;
}

.card{
  width: 30%;
}

.first-card{
  display: flex !important;
  align-items: center !important;
  justify-content: flex-end !important;
  justify-items: center !important;
  margin: 0 !important;
  width: 70%;
  margin-top: 50px !important;
  
}

}
</style>
