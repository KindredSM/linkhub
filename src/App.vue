<template>
  <img alt="Vue logo" class="logo" src="./assets/logo.png" />
  <HelloWorld msg="Kindred" />

  <iframe
    class="spotify-dropdown"
    style="border-radius: 12px"
    src="https://open.spotify.com/embed/artist/79ateW5WAiWAdVbVOWybc0?utm_source=generator&theme=0"
    height="180"
    frameBorder="0"
    allowfullscreen=""
    allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"
  ></iframe>
  <a
    href="https://open.spotify.com/artist/79ateW5WAiWAdVbVOWybc0?si=22D2BmyuSKmDsPy6qxesmg"
    target="_blank"
    ><Links msg="Spotify"></Links
  ></a>

  <a href="https://soundcloud.com/kindredwav" target="_blank"
    ><Links msg="Soundcloud"></Links
  ></a>
  <a href="https://github.com/KindredSM" target="_blank"
    ><Links msg="Github"></Links
  ></a>
  <a href="https://kindredsalway.com/" target="_blank"
    ><Links msg="Website"></Links
  ></a>
</template>

<script>
import HelloWorld from "./components/HeaderComponent.vue";
import Links from "./components/Links.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    Links,
  },
};
</script>

<style lang="scss">
body {
  background: rgb(10, 10, 10);
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.logo {
  border-radius: 50%;
  width: 6rem;
}

.spotify-dropdown {
  width: 45%;
}

@media only screen and (max-width: 768px) {
  .spotify-dropdown {
    width: 100%;
  }
}
</style>
