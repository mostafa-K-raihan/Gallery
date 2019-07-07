<template>
  <div class="__gallery-item"></div>
</template>

<script>
export default {
  name: "GalleryItem",
  props: {
    // msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.__gallery-item {
  width: 30vw;
  height: 30vh;
  background-color: red;
  margin: 2vw;
}
</style>
