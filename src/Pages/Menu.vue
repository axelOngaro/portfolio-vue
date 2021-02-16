<template>
  <div class="menu">
    <header>
      <h1 class="name">axel ongaro</h1>
      <hamburger />
      <div>media</div>
    </header>

    <nav class="nav">
      <ul>
        <li>ABOUT ME</li>
        <li>SKILLS</li>
        <li>WORK</li>
        <li>CONTACT ME</li>
      </ul>
    </nav>
  </div>
</template>

<script>
import Hamburger from "../components/Hamburger";
export default {
  name: "Menu",
  components: {
    Hamburger,
  },
};
</script>

<style scoped>
.menu {
  display: flex;
  height: 100vh;
  flex-direction: column;
}
.menu header {
  display: flex;
  justify-content: space-around;
  height: 10%;
  padding-top: 25px;
}
.nav {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 70%;
}
.nav li {
  padding: 20px 0px;
  font-size: 3rem;
}

.name {
  cursor: pointer;
}
</style>
