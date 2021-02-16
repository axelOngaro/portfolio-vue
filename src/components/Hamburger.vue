<template>
  <div class="menu-btn" @click="onClick">
    <div class="menu-btn__burger"></div>
  </div>
</template>

<script>
export default {
  name: "Hamburger",
  methods: {
    onClick() {
      console.log("coucou petite perruche");
    },
  },
};
</script>

<style lang="css" scoped>
.menu-btn {
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  width: 80px;
  height: 80px;
  cursor: pointer;
  transition: all 0.5s ease-in-out;
  border: 3px solid black;
}
.menu-btn__burger {
  width: 60px;
  height: 6px;
  background: black;
  border-radius: 5px;
  box-shadow: 0 2px 5px lightcoral;
  transition: all 0.5s ease-in-out;
}
.menu-btn__burger::before,
::after {
  content: "";
  position: absolute;
  width: 60px;
  height: 6px;
  background: black;
  border-radius: 5px;
  box-shadow: 0 2px 5px lightcoral;
  transition: all 0.5s ease-in-out;
}
.menu-btn__burger::before {
  transform: translateY(-16px);
}
.menu-btn__burger::after {
  transform: translateY(16px);
}
</style>
