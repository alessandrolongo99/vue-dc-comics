<template>
  <nav class="container d-flex justify-content-between align-items-center">
    <img src="../assets/img/dc-logo.png" alt="dc-logo">
    <ul class="d-flex align-items-center">
        <li v-for="(link, index) in navLinks" :key="index" class="fs-6 text-uppercase fw-bold">
            {{link.text}}
        </li>
    </ul>
  </nav>
</template>

<script>
export default {
    data: function(){
        return {
            navLinks:[
                {
                text: 'characters',
                url: '#'
                },
                {
                text: 'comics',
                url: '#'
                },
                {
                text: 'movies',
                url: '#'
                },
                {
                text: 'tv',
                url: '#'
                },
                {
                text: 'games',
                url: '#'
                },
                {
                text: 'collectibles',
                url: '#'
                },
                {
                text: 'videos',
                url: '#'
                },
                {
                text: 'fans',
                url: '#'
                },
                {
                text: 'news',
                url: '#'
                },
                {
                text: 'shop',
                url: '#'
                },
            ]
        }
    }
};
</script>

<style>
nav{
    padding: 1rem 0;
}

img{
    height: 5rem;
}

ul li{
    text-decoration: none;
    display: inline-block;
    padding: 1rem;
}
</style>