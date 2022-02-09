<template>
  <footer>
    <div class="footer-links">
      <div class="container">lista</div>
    </div>
    <FooterNavbar />
  </footer>
</template>

<script>
import FooterNavbar from "./FooterNavbar.vue";
export default {
  name: "Footer",
  components: {
    FooterNavbar,
  },
};
</script>

<style>
.footer-links {
  height: 500px;
  background-image: url("../assets/img/footer-bg.jpg");
  background-repeat: no-repeat;
  background-size: cover;
}
</style>