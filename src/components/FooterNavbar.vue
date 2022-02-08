<template>
  <div class="footer-navbar">
    <div class="container">
      <nav>
        <div class="btn-sign">
          <p>SIGN IN</p>
        </div>
        <div class="footer-icons">
          <ul>
            <li>
              <a href="#">FOLLOW US</a>
            </li>
            <li>
              <a href="#"
                ><img src="../assets/img/footer-facebook.png" alt=""
              /></a>
            </li>
            <li>
              <a href="#"
                ><img src="../assets/img/footer-twitter.png" alt=""
              /></a>
            </li>
            <li>
              <a href="#"
                ><img src="../assets/img/footer-youtube.png" alt=""
              /></a>
            </li>
            <li>
              <a href="#"
                ><img src="../assets/img/footer-pinterest.png" alt=""
              /></a>
            </li>
            <li>
              <a href="#"
                ><img src="../assets/img/footer-periscope.png" alt=""
              /></a>
            </li>
          </ul>
        </div>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
  name: "FooterNavbar",
};
</script>

<style lang="scss">
.footer-navbar {
  background-color: darkgray;
}

ul {
  display: flex;
  align-items: center;
}

img {
  font-size: 30px;
}

.btn-sign p {
  border: 1px solid blue;
  padding: 7px;
  cursor: pointer;
}
</style>