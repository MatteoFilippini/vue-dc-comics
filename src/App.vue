<template>
  <div class="container">
    <Header />
    <main></main>
    <footer></footer>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
export default {
  name: "App",
  components: {
    Header,
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
</style>
