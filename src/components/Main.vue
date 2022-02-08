<template>
  <main>
    <section id="content">
      <div class="container">
        <p>content</p>
      </div>
    </section>
    <Menu />
  </main>
</template>

<script>
import Menu from "./Menu.vue";
export default {
  name: "Main",
  components: {
    Menu,
  },
};
</script>

<style>
#content {
  background-color: black;
  height: 100px;
  color: white;
  display: flex;
  align-items: center;
}
</style>