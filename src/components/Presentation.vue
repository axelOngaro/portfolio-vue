<template>
  <div class="presentation">
    <p class="me">
      HI! I’M AXEL, I LIVE IN TOULOUSE, FRANCE, AND I’M A WEB DEVELOPER &
      DESIGNER. I TAKE YOUR PROJECTS FROM THE FIRST THOUGHTS TO THE FINAL
      DEPLOYMENT. MY FOCUS IS SET ON USER EXPERIENCE, PUTTING AN EMPHASIS ON
      SIMPLE AND CLEAN INTERFACE, WITH MAINTANABLE AND SCALLABLE CODE
    </p>
    <p class="me2">
      I’M FROM THE GENERATION OF PEOPLE WHO GREW UP WITH INTERNET. WE’VE SEEN
      IT’S EVOLUTIONS, AND WE ARE AWARE OF HOW POWERFULL IT IS, AND HOW MUCH THE
      SOCIETY RELIES ON IT TODAY. HAVING A PRESENCE ONLINE IS NOW A MUST FOR ANY
      BUISNESS. AND I’M HERE TO MAKE THIS HAPPEN.
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
