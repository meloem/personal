<template>
      <div class="white largeScreen">
        <div class="yellowdiv">

          <div class="centeredLeft ultimateCenteredBoth">
            <p class="intro checkIfInView"> I'm <br> Mélodie <span class="heart" id="breathing"></span></p>
          <div class="centeredRight ultimateCenteredBoth">
            <img src="../assets/mov.gif" type="video/gif" class="video">
          </div>
          </div>

        </div>
      </div>
</template>

<script>
    export default {
        name: 'Yellowdiv'
    }
</script>

<style scoped>
  
  .yellowdiv {
    z-index: 100000000000;
    position: relative;
    /*border-radius: 2px;*/
    display: inline-flex;
    width: 100%;
  }
  
  @media screen and (max-width: 480px) {
    .yellowdiv {
    }
  
    .centeredRight {
      margin: 30px;
    }
  }
  
  .video{
    width: 100%;
  }
  
  @media screen and (max-width: 480px) {
    .video {
    }
  }

    .centeredLeft {
    width: 40%;
    float: left;
  }

    /* .centeredRight {
    width: 60%;
    margin: 50px;
    float: right;
  } */

    .intro {
    font-size: 90px;
    font-weight: bold;
  }
  
  @media screen and (max-width: 480px) {
    .intro {
      font-size: 35px;
      color: black;
      text-align: center;
    }
  }
  
</style>