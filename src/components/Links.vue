<template>
  <div class="link-container">
    <h2 class="link">{{ msg }}</h2>
  </div>
</template>

<script>
export default {
  name: "Links",
  props: {
    msg: String,
  },
};
</script>

<style lang="scss">
$primaryColor: rgba(56, 56, 56, 0.5);

a {
  color: inherit;
  text-decoration: none;
}

.link-container {
  display: flex;
  justify-content: center;
  align-items: center;
  text-decoration: none;

  .link {
    text-decoration: none;
    font-weight: 700;
    background-color: $primaryColor;
    border-radius: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 1rem;
    width: 40rem;
    height: 4rem;
    color: rgb(242, 240, 240);
    transition: ease 0.2s;

    &:hover {
      background-color: rgb(55, 55, 55);
      transition: ease 0.2s;
      transform: scale(1.02);
      cursor: pointer;
    }
  }
}
</style>
