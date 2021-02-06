<template>
  <div class="like">
        <div class="div1">
          <p class="love"> I love </p>
        </div>
        <div class="div2">
          <p class="likes likes1"> Minimalism </p>
          <p class="likes likes2" style="display:none;"> Kimchi </p>
          <p class="likes likes3" style="display:none;"> Mondrian </p>
        </div>
      </div>
</template>

<script>
    export default {
        name: 'Like'
    }
</script>

<style scoped>
  .like {
    width: 100%;
    height: 750px;
    z-index: 100000000000;
    position: relative;
    background-color: #00207E;
    border-radius: 2px;
  }
  
  @media screen and (max-width: 480px) {
    .like {
      width: 100%;
      height: 440px;
      z-index: 100000000000;
    }
  }
  
  .likes {
    font-size: 30px;
    text-align: center;
    list-style-type: none;
    position: relative;
    z-index: 1000;
    top:20px;
    font-weight: 600;
    letter-spacing: -2px;
  }
  
  .likes1 {
    color:#1F3A93;
  }
  
  .likes2 {
    color:#049372;
  }
  
  .likes3 {
    color:#F39C12;
  }
  
  .love {
    color: white;
    position: relative;
    top: 200px;
    margin-left: 38%;
    font-size: 50px;
    font-weight: 600;
    letter-spacing: -2px;
  }
  
  @media screen and (max-width: 480px) {
    .love {
      color: white;
      position: relative;
      top: 65px;
      text-align: center;
      font-size: 50px;
      font-weight: 600;
      letter-spacing: -2px;
    }
  }
  
  
  .div2 {
    width: 195px;
    height: 80px;
    background-color: white;
    position: relative;
    top: 250px;
    margin-right: auto;
    margin-left: 50%;
    z-index: 100;
  }
  
  .largeScreen{
    max-width:1360px;
    margin-left: auto;
    margin-right: auto;
    position: static;
  }
  
  @media screen and (max-width: 480px) {
    .div2 {
      width: 195px;
      height: 80px;
      background-color: white;
      position: relative;
      top: 110px;
      margin-right: auto;
      margin-left: auto;
      z-index: 100;
    }
  }
</style>