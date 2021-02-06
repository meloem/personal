<template>
      <div class="map">
        <div class="center">
          <!-- <img src="./assets/map2.png" class="europe checkIfInView"> -->
        </div>
      </div>
</template>

<script>
    export default {
        name: 'Map'
    }
</script>

<style scoped>
  .map {
    width: 100%;
    position: relative;
    background-color: black;
    /*top: 10px;*/
  }
  
  @media screen and (max-width: 480px) {
    .map {
      width: 100%;
      height: 250px;
      position: relative;
      background-color: black;
      /*top: 100px;*/
    }
  }

    .center {
    margin-left: auto;
    margin-right: auto;
    text-align: center;
  }
</style>