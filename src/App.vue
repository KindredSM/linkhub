<template>
  <img alt="Kindred logo" class="logo" src="./assets/logo.png" />
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
  <a href="https://kindredsm.github.io/kindred-music/#/" target="_blank"
    ><Links msg="Website"></Links></a
  ><a
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
    ><Links msg="Developer Portfolio"></Links
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
  background: url("./assets/bg.png");
  background-size: cover;
  background-attachment: fixed;
  background-position: center;
  background-color: rgb(10, 10, 10);
  padding: 24px 12px;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  margin-bottom: 100px;
}

.logo {
  border-radius: 50%;
  width: 6rem;
  box-shadow: 0 0 3px 5px rgb(0, 0, 0);
}

.spotify-dropdown {
  padding-top: 20px;
  width: 45%;
}

@media only screen and (max-width: 768px) {
  .spotify-dropdown {
    width: 100%;
  }
}
</style>
