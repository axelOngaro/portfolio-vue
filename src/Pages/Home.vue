<template>
  <div class="home">
    <Header />
    <Presentation />
    <Technologies />
    <MyWork />
    <ContactMe />
  </div>
</template>
<script>
import Header from '../components/Header';
import MyWork from '../components/MyWork';
import Presentation from '../components/Presentation';
import Technologies from '../components/Technologies.vue';
import ContactMe from '../components/ContactMe';
export default {
  name: 'Home',
  components: {
    Header,
    Presentation,
    Technologies,
    MyWork,
    ContactMe,
  },
};
</script>
