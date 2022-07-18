<template>
  <nav class="container d-flex justify-content-between align-items-center px-0">
    <img src="../assets/img/dc-logo.png" alt="dc-logo">
    <ul class="d-flex align-items-center m-0">
        <li v-for="(link, index) in dcComicsLinks" :key="index" class="fs-6 text-uppercase fw-bold">
            <a href="#">{{link.text}}</a>
        </li>
    </ul>
  </nav>
</template>

<script>
export default {
    data: function(){
        return {
            dcComicsLinks:[
                {
                text: 'characters',
                },
                {
                text: 'comics',
                },
                {
                text: 'movies',
                },
                {
                text: 'tv',
                },
                {
                text: 'games',
                },
                {
                text: 'collectibles',
                },
                {
                text: 'videos',
                },
                {
                text: 'fans',
                },
                {
                text: 'news',
                },
                {
                text: 'shop',
                },
            ]
        }
    }
};
</script>

<style scoped>
nav{
    padding: 1rem;
}

img{
    height: 5rem;
}

ul li{
    text-decoration: none;
    display: inline-block;
    padding: 1rem;
}

li a{
    text-decoration: none;
    color: black;
}
</style>