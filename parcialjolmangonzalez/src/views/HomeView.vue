<template>
  <div>
    <HeaderComponent />
    <main>
      <ImgEmisoras />
    </main>
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderComponent from "@/components/Header.vue";
import ImgEmisoras from "@/components/ImgEmisoras.vue";

export default {
  name: "HomeView",
  components: {
    HeaderComponent,
    ImgEmisoras,
  },
};
</script>
