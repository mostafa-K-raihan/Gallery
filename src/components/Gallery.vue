<template>
  <div class="__gallery">
    <GalleryItem v-for="i in 5" :key="i"/>
  </div>
</template>

<script>
import GalleryItem from "./GalleryItem";
export default {
  name: "Gallery",
  props: {
    // msg: String
  },
  components: {
    GalleryItem
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.__gallery {
  display: flex;
  align-items: flex-start;
  justify-content: start;
  width: 100vw;
  height: 100vh;
}
</style>
