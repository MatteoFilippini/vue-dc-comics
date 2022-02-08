<template>
  <section id="icons">
    <div class="container">
      <div class="menu">
        <div class="card">
          <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
          <h4>DIGITAL COMICS</h4>
        </div>
        <div class="card">
          <img src="../assets/img/buy-comics-merchandise.png" alt="" />
          <h4>DC MERCHANDISE</h4>
        </div>
        <div class="card">
          <img src="../assets/img/buy-comics-subscriptions.png" alt="" />
          <h4>SUBSCRIPTION</h4>
        </div>
        <div class="card">
          <img src="../assets/img/buy-comics-shop-locator.png" alt="" />
          <h4>COMICS SHOP LOCATOR</h4>
        </div>
        <div class="card">
          <img src="../assets/img/buy-dc-power-visa.svg" alt="" />
          <h4>DC POWER VISA</h4>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Menu",
};
</script>

<style lang="scss">
#icons {
  background-color: blue;
}
.menu {
  display: flex;
  align-items: center;
  justify-content: space-around;
  color: white;
  padding: 30px 0;
  .card {
    display: flex;
    align-items: center;
    font-size: 0.8rem;
    h4 {
      margin-left: 10px;
    }
    img {
      height: 40px;
    }
  }
}
</style>