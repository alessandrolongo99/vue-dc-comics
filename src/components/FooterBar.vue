<template>
  <div class="footer-bar-bg">
    <div class="container">
        <div class="d-flex justify-content-between align-items-center py-4">
            <div class="sign text-uppercase text-white fw-bold">
                sign-up now!
            </div>
            <div class="footer-bar-links d-flex align-items-center">
                <div class="follow text-uppercase fw-bold">follow us</div>
                <div><img src="../assets/img/footer-facebook.png" alt="footer-facebook"></div>
                <div><img src="../assets/img/footer-twitter.png" alt="footer-twitter"></div>
                <div><img src="../assets/img/footer-youtube.png" alt="footer-youtube"></div>
                <div><img src="../assets/img/footer-pinterest.png" alt="footer-pinterest"></div>
                <div><img src="../assets/img/footer-periscope.png" alt="footer-periscope"></div>
            </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.footer-bar-bg{
    background-color: #303030;
}

.sign{
    padding: .8rem 1.8rem;
    border: 2px solid #0282f9;
    display: inline;
}

.follow{
    color: #0282f9;
}

.footer-bar-links *{
    padding-left: .8rem;
}
</style>