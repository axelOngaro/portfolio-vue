<template>
  <div class="presentation">
    <p class="me">
      hi! i’m axel, i live in toulouse, france, and i’m a web developer &
      designer. i take your projects from the first thoughts to the final
      deployment. my focus is set on user experience, putting an emphasis on
      simple and clean interface, with maintanable and scallable code
    </p>
    <p class="me2">
      i’m from the generation of people who grew up with internet. we’ve seen
      it’s evolutions, and we are aware of how powerfull it is, and how much the
      society relies on it today. having a presence online is now a must for any
      buisness. and i’m here to make this happen.
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
  height: 40vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.me {
  width: 1000px;
  padding: 50px 0px;
}
.me2 {
  width: 1000px;
  padding: 50px 0px;
}
</style>
