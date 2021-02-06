<template>
    <div class="bottom">
    </div>
</template>

<script>
    export default {
        name: 'Bottom'
    }
</script>

<style scoped>
  .bottom {
      width: 85%;
      display: flex;
      align-content: center;
      justify-content: center;
      height: 15px;
      background: black;
      -moz-border-radius: 50px;
      -webkit-border-radius: 50px;
      border-radius: 50px;
      z-index: 10;
      top: 5px;
      position: static;
      margin: auto;
  }
  @media screen and (max-width: 480px) {
      .bottom {
        width: 100%;
        height: 1%;
        background: black;
        -moz-border-radius: 50px;
        -webkit-border-radius: 50px;
        border-radius: 0;
        z-index: 10;
        position: absolute;
        margin-left: auto;
        top: 404px;
      }
  }
</style>