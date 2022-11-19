<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld title="安安" msg="Welcome to Your Vue.js App" />
    <HelloWorld title="你好" msg="Welcome to Your Vue.js App" />
    <HelloWorld title="我是" msg="Welcome to Your Vue.js App" />
    <HelloWorld title="帥哥" msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
  },
};
</script>
