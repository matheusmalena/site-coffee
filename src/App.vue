<template>
  <PageHeader/>
  <Header/>
  <Main/>
</template>

<script>
import PageHeader from './components/PageHeader.vue'
import Header from './components/Header.vue'
import Main from '@/components/Main.vue'

export default {
  name: 'App',
  components: {
    PageHeader,
    Header,
    Main,
  }
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Alkalami&family=Poetsen+One&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Poetsen+One&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

#app {
  font-family: var(--poppins);
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: var(--color-primary);
  margin-top: 60px;
  margin: 0;
  padding: 0;
}

body{
  margin: 0;
  padding: 0;
}

:root{
--color-primary: #1b1b1d;
--bg-primary: #f3f4f5;
--bg-secudary: #eeeff1;
--cinza: #64646A;
--white: #ffffff;
--poppins: "Poppins", sans-serif;
--font-alkalami: "Alkalami", serif;
}

button{
  background-color: var(--color-primary);
  color: var(--white);
  border-radius: 30px;
  padding: 15px;
  border: 1px solid var(--color-primary);
  font-size: 12px;
  cursor: pointer;
}
</style>
