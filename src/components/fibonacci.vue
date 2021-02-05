<template>
  <div>
    <p>{{ value }}</p>
    <div>
      <button @click="execFib">Change</button>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    value: {
      type: Number,
      default: 0
    },
    prevValue: {
      type: Number,
      default: 1
    }
  },
  methods: {
    execFib() {
      var newValue = this.value + this.prevValue;
      this.prevValue = this.value;
      this.value = newValue;
    }
  }
};
</script>
