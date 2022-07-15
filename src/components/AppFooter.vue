<template>
<div class="container-background">
    <div class="container p-0">
        <ul class="p-0 d-flex flex-column">
          <h5 class="text-uppercase">cd comics</h5>
            <li v-for="(link, index) in footerLinks" :key="index">
                <a href="#">{{link.text}}</a>
            </li>
        </ul>
    </div>
</div>
</template>

<script>
export default {
  data: function () {
    return {
      footerLinks: [
        {
          text: "characters",
        },
        {
          text: "comics",
        },
        {
          text: "movies",
        },
        {
          text: "tv",
        },
        {
          text: "games",
        },
        {
          text: "videos",
        },
        {
            text: "news",
        }
      ],
    };
  },
};
</script>

<style scoped>
.container-background{
    background-image: url('../assets/img/footer-bg.jpg');
    padding: 3rem 0;
}

h5{
  color: white;
  padding-bottom: .8rem;
}

li{
  padding: 0;
  font-size: .8rem;
}

li a{
  color: white;
}
</style>