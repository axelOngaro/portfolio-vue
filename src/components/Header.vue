<template>
  <div class="header">
    <div class="nav">
      <div class="name">
        <h2>axel ongaro</h2>
      </div>
      <nav>
        <ul>
          <li>Home</li>
          <li>About me</li>
          <li>Work</li>
          <li>Contact me</li>
        </ul>
      </nav>
      <div class="switchColor" @click="onClick">*</div>
    </div>
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
.header {
  display: flex;
  width: 100vw;
  position: fixed;
  justify-content: center;
  align-items: center;
}
.nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 70%;
}
.name {
  cursor: pointer;
}
.switchColor {
  height: 30px;
  width: 165px;
  border: solid black 1px;
  display: flex;
  justify-content: center;
  align-items: center;
  cursor: pointer;
}
nav {
  width: 600px;
}
nav ul {
  list-style: none;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
</style>
