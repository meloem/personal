<template>
      <div class="fox">
        <div>
          <div class="head"></div>
          <div class="cone"></div>
          <div class="cone2"></div>
          <div class="eye"></div>
          <div class="eye2"></div>
          <div class="eye3" style="display:none;"></div>
        </div>
        <div class="circle"></div>
        <div class="tail">
          <div class="minitail"></div>
        </div>
      </div>
</template>

<script>
    export default {
        name: 'Renard'
    }
</script>

<style scoped>

  .fox {
    width: 30%;
    margin-left: 35%;
    margin-top: 23%;
    position: relative;
  }
  @media screen and (max-width: 480px) {
    .fox {
        margin-left: inherit;
        transform: scale(.6,.6);
        z-index: 700;
        position: absolute;
        margin-top: inherit;
        top:237px;
    }
  }

    .head {
    position: relative;
    left: 57px;
    top: 100px;
    transform: rotate(-16deg);
    transform-origin: 0 100%;
    z-index: 99;
  }
  .head:before,
  .head:after {
    position: absolute;
    content: "";
    left: 52px;
    top: 0;
    width: 52px;
    height: 92px;
    background: #D35400;
    -moz-border-radius: 50px 50px 0 0;
    border-radius: 17px -12px 0 0;
    border-bottom-left-radius: 7px;
    border-bottom-right-radius: 7px;
    border-top-left-radius: 65px;
    border-top-right-radius: 6Px;
    -webkit-transform: rotate(-45deg);
    -moz-transform: rotate(-45deg);
    -ms-transform: rotate(-45deg);
    -o-transform: rotate(-45deg);
    transform: rotate(-45deg);
    -webkit-transform-origin: 0 100%;
    -moz-transform-origin: 0 100%;
    -ms-transform-origin: 0 100%;
    -o-transform-origin: 0 100%;
    transform-origin: 0 100%;
  }
  .head:after {
    left: 0;
    -webkit-transform: rotate(45deg);
       -moz-transform: rotate(45deg);
        -ms-transform: rotate(45deg);
         -o-transform: rotate(45deg);
            transform: rotate(45deg);
    -webkit-transform-origin: 100% 100%;
       -moz-transform-origin: 100% 100%;
        -ms-transform-origin: 100% 100%;
         -o-transform-origin: 100% 100%;
            transform-origin :100% 100%;
  }
  
  .cone {
    width: 0;
    height: 0;
    border-left: 20px solid transparent;
    border-right: 20px solid transparent;
    border-bottom: 28px solid #8A2D00;
    -moz-border-radius: 50%;
    -webkit-border-radius: 50%;
    border-radius: 50%;
    z-index: 900;
    position: absolute;
    margin-left: 72px;
    margin-top: 60px;
      transform: rotate(86deg);
      transform-origin: 0 100%;
  }
  
  .cone2 {
    width: 0;
  height: 0;
  border-left: 20px solid transparent;
  border-right: 20px solid transparent;
  border-bottom: 28px solid #8A2D00;
  -moz-border-radius: 50%;
  -webkit-border-radius: 50%;
  border-radius: 58%;
  z-index: 900;
  position: absolute;
  margin-left: 170px;
  margin-top: 61px;
      transform: rotate(175deg);
      transform-origin: 0 100%;
  }
  
  .eye {
    width: 12px;
    height: 8px;
    border-bottom: 3px solid black;
    border-bottom-left-radius: 45px;
    border-bottom-right-radius: 25px;
    transform: rotate(7deg);
    transform-origin: 0 100%;
    border-top-left-radius: -151px;
    position: relative;
    position: absolute;
    top: 124px;
    left: 95px;
    z-index: 901;
  }
  
  .eye2 {
    width: 12px;
    height: 8px;
    border-bottom: 3px solid black;
    border-bottom-left-radius: 25px;
    border-bottom-right-radius: 45px;
    transform: rotate(-14deg);
    transform-origin: 0 100%;
    border-top-left-radius: -151px;
    position: relative;
    position: absolute;
    z-index: 901;
    top: 124px;
    left: 125px;
  }
  
  .tail {
    width: 258px;
    height: 46px;
    margin-left: 32px;
    margin-top: -8px;
    border-bottom: 50px solid #AB480A;
      border-bottom-left-radius: 130px;
      border-bottom-right-radius: 88px;
      transform: rotate(3deg);
      transform-origin: 0 100%;
      border-top-left-radius: 0px;
      z-index: 100;
      position: relative;
  }
  
  .minitail {
      width: 243px;
      height: 94px;
      margin-left: 26px;
      padding-top: 6px;
      border-bottom: 14px solid #8A2D00;
      border-bottom-left-radius: 224px;
      border-bottom-right-radius: 59px;
      transform: rotate(-13deg);
      transform-origin: 0 100%;
      /* border-top-right-radius: 133px; */
      border-top-left-radius: 20px;
      position: relative;
  }

    .circle {
    width: 175px;
    height: 120px;
    background: #ED640D;
    -webkit-animation:
   6s ease-out infinite normal;
    animation: breathing 5s ease-out infinite normal;
    -moz-border-radius: 50px;
    -webkit-border-radius: 50px;
    border-radius: 109px;
    margin-left: 128px;
    top: 95px;
    position: relative;
  }
</style>