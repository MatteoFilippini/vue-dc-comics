<template>
  <main>
    <MenuImage />
    <Menu />
  </main>
</template>

<script>
import Menu from "./Menu.vue";
import MenuImage from "./MenuImage.vue";
export default {
  name: "Main",
  components: {
    Menu,
    MenuImage,
  },
};
</script>

<style>
#content {
  background-color: black;
  color: white;
  display: flex;
  align-items: center;
  padding: 30px;
}
</style>