<template>
  <div class="home">
    <Header />
    <Presentation />
  </div>
</template>
<script>
import Header from '../components/Header';
import Presentation from '../components/Presentation';
export default {
  name: 'Home',
  components: {
    Header,
    Presentation,
  },
};
</script>
