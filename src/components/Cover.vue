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
  margin: 10px;
  img {
    height: 200px;
    width: 200px;
  }
}
</style>