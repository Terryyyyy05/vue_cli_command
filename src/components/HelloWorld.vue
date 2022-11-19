<template>
  <div class="hello" :class="ooxx">
    <div class="img"></div>
    <div>
      <h1>{{ title }}</h1>
      <p>{{ msg }}</p>
      <button>安安你好</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    title: String,
    msg: String,
    ooxx: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.hello {
  display: inline-flex;
  margin: 1rem;
}
.img {
  width: 8rem;
  background-color: #ccc;
}
h3 {
  margin: 40px 0 0;
}

</style>
