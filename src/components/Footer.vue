<template>
  <footer>
    <div class="footer-links"></div>
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
  height: 200px;
  background-image: url("../assets/img/footer-bg.jpg");
}
</style>