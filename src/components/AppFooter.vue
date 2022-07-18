<template>
  <div class="container-background">
    <div class="container p-0 d-flex justify-content-between">
      <div class="links-container container d-flex">
        <div class="cd-comics-links">
          <h5 class="text-uppercase">dc comics</h5>
          <ul class="p-0 d-flex flex-column">
            <li v-for="(link, index) in dcComicsLinks" :key="index">
              <a href="#">{{ link.text }}</a>
            </li>
          </ul>
          <h5 class="text-uppercase">shop</h5>
          <ul class="p-0 d-flex flex-column">
            <li><a href="#">Shop DC</a></li>
            <li><a href="#">Shop DC Collectibles</a></li>
          </ul>
        </div>
        <div class="dc-links ps-5">
          <h5 class="text-uppercase">dc</h5>
          <ul class="p-0 d-flex flex-column">
            <li v-for="(link, index) in dcLinks" :key="index">
              <a href="#">{{ link.text }}</a>
            </li>
          </ul>
        </div>
        <div class="dc-sites-links ps-5">
          <h5 class="text-uppercase">sites</h5>
          <ul class="p-0 d-flex flex-column">
            <li v-for="(link, index) in sitesLinks" :key="index">
              <a href="#">{{ link.text }}</a>
            </li>
          </ul>
        </div>
      </div>
      <div class="hidden-bg-logo"></div>
    </div>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      dcComicsLinks: [
        {
          text: "Characters",
        },
        {
          text: "Comics",
        },
        {
          text: "Movies",
        },
        {
          text: "TV",
        },
        {
          text: "Games",
        },
        {
          text: "Videos",
        },
        {
          text: "News",
        },
      ],
      dcLinks: [
        {
          text: "Terms Of Use",
        },
        {
          text: "Privacy Policy (New)",
        },
        {
          text: "Ad Choices",
        },
        {
          text: "Advertising",
        },
        {
          text: "Jobs",
        },
        {
          text: "Subscriptions",
        },
        {
          text: "Talent Workshops",
        },
        {
          text: "Privacy Policy (New)",
        },
        {
          text: "CPSC Certificates",
        },
        {
          text: "Ratings",
        },
        {
          text: "Shop Help",
        },
        {
          text: "Contact Us",
        },
      ],
      sitesLinks: [
        {
          text: "DC",
        },
        {
          text: "MAD Magazine",
        },
        {
          text: "DC Kids",
        },
        {
          text: "DC Universe",
        },
        {
          text: "DC Power Visa",
        },
      ],
    };
  },
};
</script>

<style scoped>
.container-background {
  background-image: url("../assets/img/footer-bg.jpg");
  background-size: cover;
  /* padding: 3rem 0; */
}

.links-container {
  padding: 3rem 0;
}

h5 {
  color: white;
  padding-bottom: 0.8rem;
}

li {
  padding: 0;
  font-size: 0.8rem;
}

li a {
  color: white;
}

.hidden-bg-logo {
  height: 420px;
  width: 1000px;
  background-image: url("../assets/img/dc-logo-bg.png");
  background-position: center;
  background-repeat: no-repeat;
}
</style>