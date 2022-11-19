<template>
  <div class="img">
    <img :src="link" alt="" />
    <img :src="require('@/assets/frog.svg')" alt="" />
  </div>
</template>

<script>
export default {
  name: "Images",
  props: {
    link: String,
  },
};
</script>

<style scoped lang="scss">
.img {
  width: 100vw;
  height: 10rem;
  background-color: #999;
}
</style>
