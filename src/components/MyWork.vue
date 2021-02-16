<template>
  <div class="mywork">
    <h2>MY WORK</h2>
    <div class="mywork_text">
      <p>
        THIS WEBSITE HAS BEEN ENTIRELY CREATED BY ME FROM SCRATCH, FROM THE
        FIRST LINE SKETCHED, TO THE FINAL DEPLOYMENT.
      </p>
      <p>IT’S THERE TO REPRESENT MY VISION OF HOW THE WEB SHOULD LOOK TODAY:</p>
      <p>SIMPLE, STRAIGHT-FORWARD AND FAST</p>
      <div>
        <p>
          I HAVE OTHER SIDE PROJECTS THAT ARE WORK IN PORGRESS, THEY ll COME
          VERY SOON!!!
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MyWork",
};
</script>
<style scoped>
.mywork {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
}
.mywork_text {
  margin-top: 50px;
}
.mywork_text p {
  margin-top: 25px;
}
</style>
