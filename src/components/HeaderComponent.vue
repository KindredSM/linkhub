<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>
</template>

<style lang="scss">
.hello {
  font-size: 1rem;
  color: rgb(241, 241, 241);
}
</style>
<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
  name: "LinkText",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss"></style>
