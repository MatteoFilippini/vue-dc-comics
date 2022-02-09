<template>
  <div class="card-image">
    <img :src="url" :alt="title" />
    <h4>{{ title }}</h4>
  </div>
</template>

<script>
export default {
  name: "Cover",
  props: ["url", "title"],
};
</script>

<style lang="scss" scoped>
.card-image {
  margin: 20px;
  height: 200px;
  flex-basis: calc(100% / 6);
  img {
    height: 100%;
    width: 100%;
  }
}
</style>