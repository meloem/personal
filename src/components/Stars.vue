<template>
    <div class="stars">
      <div class="star1 star" style="display:none;"></div>
      <div class="star2 star" style="display:none;"></div>
      <div class="star3 star" style="display:none;"></div>
      <div class="star4 star" style="display:none;"></div>
      <div class="star5 star" style="display:none;"></div>
      <div class="star6 star" style="display:none;"></div>
      <div class="star7 star" style="display:none;"></div>
    </div>
</template>

<script>
    export default {
        name: 'Stars'
    }
</script>

<style>
  .star1 {
    width: 10px;
    height: 10px;
    background: #CF000F;
    -moz-border-radius: 50px;
    -webkit-border-radius: 50px;
    border-radius: 70px;
    position: absolute;
    top: 80px;
    left: 212px;
    -webkit-animation: breathing 6s ease-out infinite normal;
    animation: breathing 6s ease-out infinite normal;
  }
  
  @media screen and (max-width: 480px) {
      .star1 {
          opacity: 0;
          left:100px;
      }
  }
  
  .star2 {
  width: 15px;
  height: 15px;
  background: #CF000F;
  -moz-border-radius: 50px;
  -webkit-border-radius: 50px;
  border-radius: 70px;
  position: absolute;
  top: 50px;
  left: 700px;
  -webkit-animation: breathing 6s ease-out infinite normal;
  animation: breathing 6s ease-out infinite normal;
  }
  
  @media screen and (max-width: 480px) {
      .star2 {
        width: 10px;
        height: 10px;
        background: #CF000F;
        -moz-border-radius: 50px;
        -webkit-border-radius: 50px;
        border-radius: 70px;
        position: absolute;
        top: 50px;
        left: 50px;
        -webkit-animation: breathing 6s ease-out infinite normal;
        animation: breathing 6s ease-out infinite normal;
      }
  }
  
  .star3 {
  width: 14px;
  height: 14px;
  background: #CF000F;
  -moz-border-radius: 50px;
  -webkit-border-radius: 50px;
  border-radius: 70px;
  position: absolute;
  top: 410px;
  left: 130px;
  -webkit-animation: breathing 6s ease-out infinite normal;
  animation: breathing 6s ease-out infinite normal;
  }
  @media screen and (max-width: 480px) {
      .star3 {
          opacity: 0;
      }
  }
  
  .star4 {
  width: 16px;
  height: 16px;
  background: #CF000F;
  -moz-border-radius: 50px;
  -webkit-border-radius: 50px;
  border-radius: 70px;
  position: absolute;
  top: 210px;
  left: 1050px;
  -webkit-animation: breathing 6s ease-out infinite normal;
  animation: breathing 6s ease-out infinite normal;
  }
  
  @media screen and (max-width: 480px) {
      .star4 {
          opacity: 0;
          left: 100px;
      }
  }
  
  @media screen and (min-width: 500px) and (max-width: 800px) {
      .star4 {
          opacity:0;
          left: 300px;
      }
  }
  
  .star5 {
    width: 9px;
    height: 9px;
    background: #CF000F;
    -moz-border-radius: 50px;
    -webkit-border-radius: 50px;
    border-radius: 70px;
    position: absolute;
    top: 350px;
    left: 92%;
    -webkit-animation: breathing 6s ease-out infinite normal;
    animation: breathing 6s ease-out infinite normal;
  }
  
  @media screen and (max-width: 480px) {
      .star5 {
  opacity: 0;
      }
  }
  
  .star6 {
  width: 16px;
  height: 16px;
  background: #CF000F;
  -moz-border-radius: 50px;
  -webkit-border-radius: 50px;
  border-radius: 70px;
  position: absolute;
  top: 300px;
  left: 400px;
  -webkit-animation: breathing 6s ease-out infinite normal;
  animation: breathing 6s ease-out infinite normal;
  }
  @media screen and (max-width: 480px) {
      .star6 {
        width: 10px;
        height: 10px;
        background: #CF000F;
        -moz-border-radius: 50px;
        -webkit-border-radius: 50px;
        border-radius: 70px;
        position: absolute;
        top: 100px;
        left: 85%;
        -webkit-animation: breathing 6s ease-out infinite normal;
        animation: breathing 6s ease-out infinite normal;
      }
  }
  
  .star7 {
  width: 12px;
  height: 12px;
  background: #CF000F;
  -moz-border-radius: 50px;
  -webkit-border-radius: 50px;
  border-radius: 70px;
  position: absolute;
  top: 450px;
  left: 75%;
  -webkit-animation: breathing 6s ease-out infinite normal;
  animation: breathing 6s ease-out infinite normal;
  }
  @media screen and (max-width: 480px) {
      .star7 {
        width: 9px;
        height: 9px;
        background: #CF000F;
        -moz-border-radius: 50px;
        -webkit-border-radius: 50px;
        border-radius: 70px;
        position: absolute;
        top: 275px;
        left: 70px;
        -webkit-animation: breathing 6s ease-out infinite normal;
        animation: breathing 6s ease-out infinite normal;
      }
  }
  
  @media screen and (min-width: 500px) and (max-width: 800px) {
      .star7 {
          opacity: 0;
      }
  }

</style>