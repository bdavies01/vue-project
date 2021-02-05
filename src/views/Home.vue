<template>
  <div class="home">
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
