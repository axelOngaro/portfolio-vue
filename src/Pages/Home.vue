<template>
  <div class="home">
    <Header />
    <Presentation />
    <Technologies />
  </div>
</template>
<script>
import Header from '../components/Header';
import Presentation from '../components/Presentation';
import Technologies from '../components/Technologies.vue';
export default {
  name: 'Home',
  components: {
    Header,
    Presentation,
    Technologies,
  },
};
</script>
