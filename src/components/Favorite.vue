<template>
    <section class="d-flex flex-md-row w-100 justify-content-center">
    <div class="w-50">
        <img src="https://i.postimg.cc/Sx9GjbtM/3-copos-removebg-preview.png" alt="">
    </div>
    <div class="d-flex flex-column w-25 align-items-center favorite-text">
       <h2>Order Your Favorite Coffee</h2>
        <p class="w-75 d-flex justify-content-start">Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint. Velit officia consequat duis enim velit mollit. Exercitation veniam
consequat sunt nostrud amet.</p>
        <button>ORDER NOW</button>
    </div>
</section>
</template>


<script>
export default {
    // eslint-disable-next-line vue/multi-word-component-names
    name: "Favorite",
}
</script>

<style scoped>

section{
    background: linear-gradient(0deg, rgba(255,255,255,1) 0%, rgba(238,239,241,1) 38%);
}

h2{
    font-size: 50px;
    font-weight: 600;
}

img{
    width: 70%;
    height: auto;
}

button{
    width: 50%;
    height: auto;
    border-radius: 30px;
    margin-top: 30px;
}

p{
    text-align: left;
}


@media screen and (max-width: 900px) {
    h2{
    font-size: 24px;
    font-weight: 600;
}

p{
    font-size: 12px;
}

section{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 2rem;
}

.favorite-text{
    width: 80% !important;
}


}
</style>