<template>
  <div class="technologies">
    <h2>Some of the technologies i like to use:</h2>
    <ul>
      <li><h2>REACT & VUE</h2></li>
      <li><h2>NODE & EXPRESS</h2></li>
      <li><h2>MONGODB & POSTGRESQL</h2></li>
      <li><h2>DOCKER & KUBERNETES</h2></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Technologies",
};
</script>

<style scoped>
.technologies {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
}
h2 {
  margin-bottom: 50px;
}
</style>
