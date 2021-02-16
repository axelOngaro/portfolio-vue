<template>
  <div class="presentation">
    <p class="me">
      Hi! I’m Axel, I live in Toulouse, France, and I’m a web developer &
      designer. I take your projects from the first thoughts to the final
      deployment. My focus is set on User experience, putting an emphasis on
      simple and clean interface, with maintanable and scallable code
    </p>
    <p class="me2">
      I’m from the generation of people who grew up with internet. We’ve seen
      it’s evolutions, and we are aware of how powerfull it is, and how much the
      society relies on it today. Having a presence online is now a must for any
      buisness. And I’m here to make this happen.
    </p>
  </div>
</template>
<script>
export default {
  name: "Presentation",
};
</script>
<style scoped>
.presentation {
  height: 100vh;

  display: flex;
  flex-direction: column;
  justify-content: space-around;
  align-items: center;
}
.me {
  width: 50%;
}
.me2 {
  width: 50%;
}
</style>
