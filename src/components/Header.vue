<template>
  <div class="Header">
    <h1>Hello there</h1>
    <div class="switchColor" @click="onClick">*</div>
  </div>
</template>
<script>
export default {
  name: "Header",
  methods: {
    onClick() {
      this.$emit("onClick");
    },
  },
};
</script>

<style scoped>
.Header {
  height: 100vh;
}
.switchColor {
  height: 30px;
  width: 30px;
  border: solid black 1px;
  display: flex;
  justify-content: center;
  align-items: center;
  cursor: pointer;
}
</style>
