<template>
  <div class="home">
    <AboutComp asd="Hello" />
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import AboutComp from "@/components/AboutComp.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
    AboutComp
  },
};
</script>
