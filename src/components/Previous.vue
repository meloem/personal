<template>
      <div class="previous">
      <p class="worknstudy3 checkIfInView"> A couple of things I've had fun doing </p>
        <div class="squares">

          <div class="row1 hidden-md-down checkIfInView">
            <div class="things">
              <!-- <img src="../assets/iot1.jpg" class="pointer iot1" onclick="window.open(this.src)"> -->
            </div>
          </div>
          <div class="row2 hidden-md-down checkIfInView">
            <div class="things">
              <img src="../assets/kimchi.jpg" class="pointer kimchi" onclick="window.open(this.src)">
            </div>
            <div class="things">
              <img src="../assets/srcleaflet.jpg" class="pointer srcleaflet" onclick="window.open(this.src)">
            </div>
            <div class="things">
              <img src="../assets/cool.jpg" class="pointer japround" onclick="window.open(this.src)">
            </div>
          </div>
          <div class="row3 hidden-md-down checkIfInView">
            <div class="things">
              <a href="https://melo.li/src/">
                <img class="srcweb" src="../assets/s.png" >
              </a>
            </div>
          </div>
         
          <div class="row4 hidden-md-down checkIfInView">
            <div class="things">
              <img src="../assets/europol.png" class="pointer europol" onclick="window.open(this.src)">
            </div>

            <div class="things">
              <img src="../assets/flowers.gif" class="pointer flowers" onclick="window.open(this.src)">
            </div>
          </div>
          
          <div class="row900 hidden-md-down checkIfInView">
            <div class="things">
              <img style="width: 72%;" src="../assets/helloworld.jpg" class="pointer din" onclick="window.open(this.src)">
            </div>
          </div>

          <div class="row5 hidden-md-down checkIfInView">
            <div class="things">
              <a href="https://invis.io/EUZ2E09SCKX#/434401701_IPhone_6_Wireframe1-01"></a>
              <img src="../assets/din.png" class="pointer din" onclick="window.open(this.src)">
            </div>
            <div class="things">
              <img src="../assets/hello.png" class="pointer korea" onclick="window.open(this.src)">
            </div>
          </div>
         
        </div>
      </div>
</template>

<script>
    export default {
        name: 'Previous'
    }
</script>

<style scoped>
  .previous {
    width: 100%;
    z-index: 100000000000;
    position: relative;
    background-color: black;
    border-radius: 2px;
    padding-bottom: 190px;
  }
  
  @media screen and (max-width: 480px) {
    .previous {
  display: none;
    }
  }
  
  .pointer {
    cursor: pointer !important;
  }
  
  .europol {
  width: 35%;
  margin: 30px;
  padding-bottom: 75px;
  }
  
  .japround {
  width: 25%;
  margin: 50px;
  }
  
  .iot1 {
  width: 65%;
  margin: 50px;
  }
  
  .iot2 {
  width: 20%;
  margin: 30px;
  padding-bottom: 40px;
  }
  
  .flowers {
  width: 37%;
  margin: 30px;
  padding-bottom: 74px;
  }
  
  .kimchi {
  width: 25%;
  margin: 50px;
  }
  
  .din {
  width: 20%;
  margin: 30px;
  }
  
  .srcleaflet {
  width: 23%;
  margin: 49px;
  }
  
  .korea {
  width: 50%;
  margin: 20px;
  padding-bottom: 50px;
  }
  
  .srcweb {
  width: 70%;
  margin: 30px;
  }
  
  .squares {
  top: 100px;
  position: relative;
  display: inline;
  }
  
  .things {
  display: inline;
  }
  
  .helloworld {
    width: 70%;
    margin: 30px;
    }
  
  .row1 {
  position: relative;
  margin-left: 21.5%;
  }
  
  .row2 {
  position: relative;
  margin-left:5%;
  }
  
  .row3 {
  position: relative;
  margin-left: 20%;
  }
  
  .row4 {
    position: relative;
    margin-left: 16%;
    top: 30px;
  }
  
  .row5 {
  width: 83%;
  position: relative;
  margin-left: 17%;
  top: 30px;
  }
  
  .row900 {
    position: relative;
    margin-left: 20%;
    }

      .worknstudy3 {
    position: relative;
    top: 100px;
    color: #F4D03F;
    text-align: center;
    font-size: 50px;
    font-weight: 600;
    letter-spacing: -2px;
    line-height: 1;
  }

    .europe {
    margin-top: 40px;
    position: relative;
    margin-bottom: 60px;
    width: 85%;
    max-width: 1300px;
  }
</style>