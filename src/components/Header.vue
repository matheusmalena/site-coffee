<template>
  <section class="d-flex justify-content-around align-items-center padding-top">
    <div class="text-header w-25 p-3 d-flex flex-column align-items-start gap-4">
      <h1>Divina Delicious Coffee <img class="selo" src="../../public/assets/selo.png" alt="" /></h1>
      <p>
        A drink from the 'My Divina' bootle brews range OR grap one of our delicious
        coffee´s
      </p>
      <div class="d-flex row">
      <button class="btn-download">DONWLOAD APP</button>
      <button class="btn-buy">SHOP COFFEE</button>
    </div>
    </div>
    <div class="w-40 d-flex align-items-center justify-content-center ">
      <img class="img-copo" src="../../public/assets/copo.png" alt="" />
    </div>
  </section>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Header",
};
</script>

<style scoped>
h1 {
  font-family: var(--font-alkalami);
  font-size: 120px;
  font-weight: 800;
  color: var(--color-primary);
  margin: 0%;
}

.text-header{
  text-align: left;
}

.padding-top {
  padding: 8rem !important;
}

p {
  font-family: var(--poppins);
  font-weight: 400;
  font-size: 14px;
}

section {
  background-color: var(--bg-secudary);
}

button {
  width: 200px;
  font-family: var(--poppins);
  font-weight: 600;
  font-size: 14px;
}

.img-copo {
  width: 100%;
  height: 100%;
}

.selo {
  width: 50px;
  height: 40px;
}

.btn-download {
  background-color: var(--color-primary);
  color: var(--white);
  border-radius: 30px;
  padding: 15px;
  border: 1px solid var(--color-primary);
  cursor: pointer;
}

.btn-buy {
  color: var(--color-primary);
  background: none;
  border: none;
  padding: 15px;
  cursor: pointer;
  text-decoration: underline;
}

@media screen and (max-width: 900px) {
  .img-copo {
    width: 100%;
    height: auto;
  }

  h1 {
    font-size: 30px;
  }

  p {
    font-size: 12px;
  }

  button {
    font-size: 10px;
  }
}

@media screen and (max-width: 400px) {
  .img-copo {
    width: 100%;
    height: auto;
  }
}
</style>
