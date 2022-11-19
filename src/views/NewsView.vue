<template>
  <div class="news">
    <Images link="https://fakeimg.pl/100" />
    <h1>This is a news-page</h1>
    <HelloWorld title="帥哥" ooxx='test-type' msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import HelloWorld from "@/components/HelloWorld.vue";
import Images from "@/components/Images.vue";

export default {
  name: "NewsView",
  components: {
    HelloWorld,
    Images
  },
};
</script>

<style scoped lang="scss">
.test-type {
  background-color: rgb(81, 215, 211);
  
}
</style>
