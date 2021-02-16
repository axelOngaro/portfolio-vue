<template>
  <div :class="currentStyle">
    <Header @onClick="colorSwitch" />
    <Presentation />
    <Technologies />
    <MyWork />
    <ContactMe />
  </div>
</template>
<script>
import Header from "../components/Header";
import MyWork from "../components/MyWork";
import Presentation from "../components/Presentation";
import Technologies from "../components/Technologies.vue";
import ContactMe from "../components/ContactMe";
export default {
  name: "Home",
  data() {
    return {
      StyleList: ["home", "home1", "home2"],
      currentStyle: "home",
      styleIterator: 0,
    };
  },
  components: {
    Header,
    Presentation,
    Technologies,
    MyWork,
    ContactMe,
  },
  methods: {
    colorSwitch() {
      if (this.styleIterator === this.StyleList.length - 1) {
        this.styleIterator = 0;
      } else {
        this.styleIterator = this.styleIterator + 1;
      }
      this.currentStyle = this.StyleList[this.styleIterator];
    },
  },
};
</script>
<style scoped>
.home {
  background-color: #fff9f2;
  color: black;
}
.home1 {
  background-color: black;
  color: white;
}
.home2 {
  background-color: blue;
  color: red;
}
</style>
