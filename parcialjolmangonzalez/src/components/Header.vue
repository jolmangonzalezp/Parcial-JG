<template>
  <div>
    <nav class="menu">
      <!-- <router-link to="/">Emisoras</router-link> |
    <router-link to="/about">Podcast</router-link>
    <router-link to="/about">Mi Lista</router-link>
    <router-link to="/about">Podcast</router-link> -->
      <li>Emisoras</li>
      <li>Podcast</li>
      <li>Mi Lista</li>
      <li>Podcast</li>
    </nav>
  </div>
</template>

<script>
export default {
  name: "HeaderComponent",
};
</script>

<style scoped>
nav {
  width: 100%;
  height: 80px;
  background: #455a64;
  display: flex;
  color: #fff;
}

nav li {
  width: 25%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}

nav li:hover {
  border-bottom: 2px solid #fff;
}
</style>
