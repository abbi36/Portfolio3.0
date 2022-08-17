<template>
  <div class="about">
    <h1>Born & raised in Kansas City.</h1>
    <div class="cityPic">
      <img src="../assets/KansasCity.png" alt="">
    </div>
    <div class="dogs">
      <img src="../assets/otis.png">
      <img src="../assets/rocko.png">
  </div>
  <div class="otis">
    <h1>Name: Otis</h1>
    <h2>Strengths: Sleeping, Drooling, Swimming</h2>
    <h2>Weaknesses: Bubbles, Baths, Loud Noises</h2>
  </div>
  <div class="rocko">
    <h1>Name: Rocko</h1>
    <h2>Strengths: Barking, Chasing Squirrels, Begging</h2>
    <h2>Weaknesses: Groundhogs.</h2>
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

  .dogs img{
    display: flex;
    margin-left: 10%;
    margin-top: 15%;
    width: 20%;
    height: auto;
  }

  .otis {
    margin-top: -70%;
    margin-left: 0%;
  }

  .rocko {
    margin-top: 35%;
    margin-left: 5%;
  }

</style>