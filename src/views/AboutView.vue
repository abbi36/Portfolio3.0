<template>
  <div class="about">
    <h1>Born & raised in Kansas City.</h1>
    <div class="cityPic">
      <img src="../assets/KansasCity.png" alt="">
    </div>
  </div>
</template>

<script scoped>
export default {
  name: 'AboutView',
}
</script>

<style scoped>

  .cityPic {
    display: flex;
    justify-content: center;
    animation-name: floating;
    animation-duration: 3s;
    animation-iteration-count: infinite;
    animation-timing-function: ease-in-out;
    width: 100%;
  }

  @keyframes floating {
    0% { transform: translate(0,  0px); }
    50%  { transform: translate(0, 15px); }
    100%   { transform: translate(0, -0px); }   
}
</style>