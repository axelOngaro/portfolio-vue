<template>
  <div class="mywork">
    <h2>MY WORK</h2>
    <div class="mywork_text">
      <p>
        this website has been entirely created by me from scratch, from the
        first line sketched, to the final deployment.
      </p>
      <p>it’s there to represent my vision of how the web should look today:</p>
      <p>simple, straight-forward and fast</p>
      <div>
        <p>
          i have other side projects that are work in porgress, they ll come
          very soon!!!
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
  height: 50vh;
}
.mywork_text {
  margin-top: 50px;
  width: 1000px;
}
.mywork_text p {
  margin-top: 25px;
}
</style>
