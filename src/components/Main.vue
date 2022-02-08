<template>
  <main>
    <section id="content">
      <p>content</p>
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