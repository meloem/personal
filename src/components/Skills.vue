<template>
      <div class="skillsdiv">
        <div class="center lotsskills" style="max-width:1300px;">
          <p class="worknstudy2 checkIfInView"> A few skills </p>

        <div class="row6">
          <div class="skillsCommons color4 skills1 skillsGeneral shakyshaky">
            <p class="fewskills5"> Illustrator </p>
          </div>
          <div class="skillsCommons color2 skills3 skillsGeneral shakyshaky">
            <p class="fewskills4"> HT<br>ML </p>
          </div>
          <div class="skillsCommons color3 skills4 skillsGeneral shakyshaky">
            <p class="fewskills"> Illustration </p>
          </div>
        </div>

        <div class="row7">
          <div class="skillsCommons color2 skills5 skillsGeneral shakyshaky">
            <p class="fewskills4"> Leadership </p>
          </div>
          <div class="skillsCommons color3 skills6 skillsGeneral shakyshaky">
            <p class="fewskills"> InVision </p>
          </div>
          <div class="skillsCommons color2 skills9 skillsGeneral shakyshaky">
            <p class="fewskills4"> Photoshop </p>
          </div>
          <div class="skillsCommons color4 skills8 skillsGeneral shakyshaky">
            <p class="fewskills"> After <br> Effects </p>
          </div>
        </div>

        <div class="row8">
          <div class="skillsCommons color4 skills10 skillsGeneral shakyshaky">
            <p class="fewskills5"> Web design </p>
          </div>
          <div class="skillsCommons color2 skills2 skillsGeneral shakyshaky">
            <p class="fewskills4"> CSS </p>
          </div>
          <!-- <div class="skillsCommons color1 skills13 skillsGeneral shakyshaky">
            <p class="fewskills5">  After Effects </p>
          </div> -->
          <div class="skillsCommons color4 skills14 skillsGeneral shakyshaky">
            <p class="fewskills"> Content design </p>
          </div>
          <div class="skillsCommons color3 skills15 skillsGeneral shakyshaky">
            <p class="fewskills"> Spanish </p>
          </div>
        </div>

      </div>
      </div>
</template>

<script>
    export default {
        name: 'Skills'
    }
</script>

<style scoped>
@media screen and (max-width: 480px) {
      .worknstudy {
        position: relative;
        top: 180px;
        text-align: center;
        font-size: 25px;
        font-weight: 600;
        letter-spacing: -2px;
        line-height: 1;
      }
    }
  
  
  .skillsdiv {
    width: 100%;
    z-index: 100000000000;
    position: relative;
    background-color: #00207E;
    border-radius: 2px;
    padding-bottom: 190px;
    height: 600px;
  }
  
  @media screen and (max-width: 1080px) {
    .skillsdiv, .previous {
      display: none;
    }
  }
  
  .skills1 {
    width: 200px;
    height: 60px;
    top: 35px;
    left: 200px;
    transform: rotate(-7deg);
  }
  
  @media screen and (min-width: 500px) and (max-width: 800px) {
    .skills1 {
      width: 140px;
      height: 45px;
      top: 24px;
      left: -69px;
      transform: rotate(0deg);
    }
  }
  
  .skills2 {
    width: 80px;
    height: 60px;
    top: 0px;
    left: 140px;
  }
  
  @media screen and (min-width: 500px) and (max-width: 800px) {
    .skills2 {
      width: 65px;
      height: 45px;
      top: 129px;
      left: 90px;
    }
  }
  
  .skills3 {
    width: 100px;
    height: 95px;
    top: 25px;
    left: 15px;
    transform: rotate(10deg);
  }
  
  @media screen and (min-width: 500px) and (max-width: 800px) {
    .skills3 {
      width: 80px;
      height: 70px;
      top: 60px;
      left: 125px;
      transform: rotate(0deg);
    }
  }
  
  .skills4 {
    width: 175px;
    height: 60px;
    top: 101px;
    left: 85px;
  }
  
  @media screen and (min-width: 500px) and (max-width: 800px) {
      .skills4 {
        width: 90px;
        height: 45px;
        top: 136px;
        left: 132px;
      }
    }
  
  .skills5 {
    width: 170px;
    height: 60px;
    top: 23px;
    left: 285px;
  }
  
  @media screen and (min-width: 500px) and (max-width: 800px)  {
    .skills5 {
      width: 130px;
      height: 45px;
      top: 75px;
      left: 170px;
    }
  }
  
  .skills6 {
    width: 170px;
    height: 60px;
    left: 140px;
    top: 70px;
  }
  
  @media screen and (min-width: 500px) and (max-width: 800px) {
    .skills6 {
      width: 130px;
      height: 45px;
      top: -91px;
      left: 106px;
    }
  }
  
  .skills7 {
    width: 140px;
    height: 60px;
    top: -126px;
    left: -350px;
  }
  
  @media screen and (min-width: 500px) and (max-width: 800px) {
    .skills7 {
      width: 100px;
      height: 45px;
      top: 22px;
      left: 127px;
    }
  }
  
  .skills8 {
    width: 120px;
    height: 90px;
    top: 55px;
    left: 345px;
  }
  
  @media screen and (min-width: 500px) and (max-width: 800px) {
    .skills8 {
      width: 70px;
      height: 70px;
      top: 100px;
      left: 176px;
  
    }
  }
  
  .skills9 {
    width: 150px;
    height: 60px;
    left: 90px;
    top: 190px;
  }
  
  @media screen and (min-width: 500px) and (max-width: 800px) {
    .skills9 {
      width: 105px;
      height: 45px;
      left: 150px;
      top: 57px;
    }
  }
  
  .skills10 {
    width: 160px;
    height: 60px;
    top: -35px;
    left: 75px;
  }
  
  @media screen and (min-width: 500px) and (max-width: 800px) {
    .skills10 {
      width: 130px;
      height: 45px;
      top: 365px;
      left: 304px;
    }
  }
  
  
  .skills12 {
    width: 55px;
    height: 125px;
    top: -90px;
    left: 245px;
  }
  
  @media screen and (min-width: 500px) and (max-width: 800px) {
    .skills12 {
      width: 50px;
      height: 100px;
      top: -50px;
      left: 242px;
      transform: rotate(0deg);
    }
  }
  
  .skills13 {
  width: 240px;
  height: 60px;
  top: 100px;
  left: 700px;
  }
  
  @media screen and (min-width: 500px) and (max-width: 800px) {
    .skills13 {
      width: 95px;
      height: 70px;
      top: -60px;
      left: 83px;
      transform: rotate(0deg);
    }
  }
  
  .skills14 {
    width: 200px;
    height: 60px;
    top: 175px;
    left: 150px;
    transform: rotate(10deg);
  
  }
  
  @media screen and (min-width: 500px) and (max-width: 800px) {
    .skills14 {
      width: 140px;
      height: 45px;
      top: 45px;
      left: 57px;
      transform: rotate(0deg);
    }
  }
  
  .skills15 {
    width: 130px;
    height: 60px;
    top: -35px;
    left: 145px;
    transform: rotate(-10deg);
  }
  
  @media screen and (min-width: 500px) and (max-width: 800px) {
    .skills15 {
      width: 100px;
      height: 45px;
      top: -126px;
      left: 75px;
      transform: rotate(0deg);
    }
  }
  
  
  .skillsCommons {
    border-radius: 43px;
    position: relative;
  }
  
  .color1 {
    background-color: black;
    color: white;
  }
  
  .color2 {
    background-color: #F4D03F;
    color: #00207E;
  }
  
  .color3 {
    background-color: black;
    color:white;
  }
  
  .color4 {
    background-color: #FF3062;
    color:black;
  }
  
  .fewskills {
    text-align: center;
    font-size: 23px;
    align-items: center;
    padding-top: 13px;
  }
  
  .fewskills2 {
    text-align: end;
    font-size: 23px;
    align-items: center;
    writing-mode: horizontal-tb;
    text-orientation: mixed;
    letter-spacing: 5.2px;
    padding-top: 13px;
  }
  
  .fewskills3 {
    text-align: center;
    font-size: 21px;
    align-items: center;
    writing-mode: vertical-lr;
    text-orientation: sideways;
    letter-spacing: 5.2px;
    padding-top: 13px;
  }
  
  .fewskills4 {
    text-align: center;
    font-size: 23px;
    align-items: center;
    padding-top: 13px;
  }
  
  .fewskills5 {
    text-align: center;
    font-size: 23px;
    align-items: center;
    padding-top: 13px;
  }

    .row6 {
  display: inline-table;
  position: relative;
  top: 60px;
  }
  
  .row7 {
  display: inline-table;
  position: relative;
  top: 100px;
  }
  
  @media screen and (max-width: 480px) {
    .row7 {
      display: inline-table;
      position: relative;
      top: 100px;
      left:0%;
    }
  }
  
  .row8 {
  display: inline-table;
  position: absolute;
  top: 200px;
  left: 3%;
  }
  
  .lotsskills {
    max-width: 1300px;
    width: 100%;
    position: relative;
  }

    .worknstudy2 {
    position: relative;
    top: 100px;
    text-align: center;
    font-size: 50px;
    font-weight: 600;
    letter-spacing: -2px;
    line-height: 1;
    color: #f4d03f;
  }
</style>