<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <fibonacci />
  </div>
</template>

<script>
// @ is an alias to /src
import fibonacci from "@/components/fibonacci.vue";

export default {
  name: "Home",
  components: {
    fibonacci
  }
};
</script>
