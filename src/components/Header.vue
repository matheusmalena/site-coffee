<template>
  <section class="d-flex gap-5">
    <div class="text-header w-50 p-3">
      <h1>Divina Delicious Coffee</h1>
      <img class="selo" src="/public/assets/selo.png" alt="" />
      <p>
        A drink from the 'My Divina' bootle brews range OR grap one of our delicious
        coffee´s
      </p>
      <button class="btn-download">DONWLOAD APP</button>
      <button class="btn-buy">SHOP COFFEE</button>
    </div>
    <div>
      <img class="img-copo" src="/public/assets/copo.png" alt="" />
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
  font-size: 80px;
  font-weight: 800;
  color: var(--color-primary);
  margin: 0%;
}

p {
  font-family: var(--poppins);
  font-weight: 400;
  font-size: 14px;
}

section{
  background-color: var(--bg-secudary);
}

button {
  font-family: var(--poppins);
  font-weight: 600;
  font-size: 14px;
}

.img-copo {
  width: 50vh;
  height: 60vh;
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
</style>
