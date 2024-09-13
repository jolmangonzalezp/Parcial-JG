<template>
  <div>
    <section class="emisoras-images">
      <div class="item" v-for="emisora in emisoras" :key="emisora.id">
        <img :src="emisora.image" />
      </div>
    </section>
  </div>
</template>

<script>
import axios from "axios";
export default {
  name: "ImgEmisoras",
  methods: {
    showItems: async function () {
      await axios
        .get("https://cobuses.com.co/APIV2/model/radio.php?dato=getallemisoras")
        .then((response) => {
          console.log(response);
        });
    },
  },
};
</script>
