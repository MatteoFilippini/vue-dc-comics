<template>
  <header>
    <nav>
      <figure>
        <img src="../assets/img/dc-logo.png" alt="" />
      </figure>
      <ul>
        <li
          v-for="link in links"
          :key="link.text"
          :class="{ active: link.active }"
        >
          <a :href="link.url" :class="{ active: link.active }">{{
            link.text
          }}</a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      links: [
        { text: "CHARACTERS", url: "#", active: false },
        { text: "COMICS", url: "#", active: true },
        { text: "MOVIES", url: "#", active: false },
        { text: "TV", url: "#", active: false },
        { text: "GAMES", url: "#", active: false },
        { text: "COLLECTIBLES", url: "#", active: false },
        { text: "VIDEOS", url: "#", active: false },
        { text: "NEWS", url: "#", active: false },
        { text: "SHOP", url: "#", active: false },
      ],
    };
  },
};
</script>

<style lang="scss">
figure {
  img {
    height: 70px;
  }
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 0;
}

ul {
  display: flex;
}

li {
  list-style-type: none;
  padding: 20px 10px;
  a {
    color: black;
    font-size: 12px;
    font-weight: bold;
    &.active {
      color: blue;
    }
    &:hover {
      color: blue;
    }
  }
}
</style>