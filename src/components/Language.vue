<template>
    <div class="language">
                <div style="z-index: 990;" class="containerLang">
          <h1 class="mainLang text-animated-1"> Bonjour </h1>
          <h1 class="mainLang text-animated-2"> Hej </h1>
          <h1 class="mainLang text-animated-3"> 안녕하세요 </h1>
          <h1 class="mainLang text-animated-4"> こんにちは </h1>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Language'
    }
</script>

<style scoped>
  .mainLang {
    color: black;
    font-size: 80px;
  }
  
  @media screen and (max-width: 480px) {
  .mainLang {
      color: black;
      font-size: 40px;
      top:-10px;
    }
  }
  
  .containerLang {
    position: relative;
    top: 40px;
    /* left: 40px; */
    display: flex;
    text-align: center;
    justify-content: center;
  }
  
  @media screen and (max-width: 480px) {
    h1 {
      color: black;
      font-size: 16px;
      position: relative;
      top: 70px;
      /* left: 40px; */
      display: flex;
      text-align: center;
      justify-content: center;
    }
  }
  
  @media screen and (max-width: 480px) {
    a {
      color: black;
      font-size: 15px;
      position: relative;
      top: 40px;
      display: flex;
      text-align: center;
      justify-content: center;
      text-decoration: none;
    }
  }
</style>