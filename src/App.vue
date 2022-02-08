<template>
  <div class="container">
    <Header />
    <Main />
    <footer></footer>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
export default {
  name: "App",
  components: {
    Header,
    Main,
  },
};
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container {
  margin: 0 auto;
  width: 1080px;
  max-width: 100%;
}

a {
  text-decoration: none;
}
</style>
