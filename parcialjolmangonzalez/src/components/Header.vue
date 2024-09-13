<template>
  <nav>
    <router-link to="/">Emisoras</router-link> |
    <router-link to="/about">Podcast</router-link>
    <router-link to="/about">Mi Lista</router-link>
    <router-link to="/about">Podcast</router-link>
  </nav>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<style scoped>

</style>
