<template>
      <div class="finaldiv">
        <div class="lastdiv">
        <p class="worknstudy checkIfInView"> I would <span style="color:#ff3062;"> love </span> to meet you </p>
        <div class="end">
          <div class="end1">
            <p class="final">
              <a onclick="void(0)" style="z-index: 991; text-decoration:none; color: #00207E;" href="mailto:melo.em@gmail.com">Email</a>
            </p>
          </div>
          <div class="end2">
            <p class="final">
              <a onclick="void(0)" style="z-index: 991; text-decoration:none; color: #00207E;" href="https://twitter.com/melo_emre">Twitter</a>
            </p>
          </div>

          <div class="end4">
            <p class="final">
              <a onclick="void(0)" style="z-index: 991; text-decoration:none; color: #00207E;" href="cv.pdf">CV</a>
            </p>
          </div>
        </div>
        <div class="bottomright">
          <p class="name"> Mélodie.</p>
        </div>
      </div>
      </div>
</template>

<script>
    export default {
        name: 'Final'
    }
</script>

<style scoped>
 .mail:hover {
    text-decoration: none;
    color: #22313F;
  }
  
  .twitter:hover {
    text-decoration: none;
    color: #22313F;
  }
  
  .mail:focus .twitter:focus {
    display:block;
  }

   .finaldiv {
    width: 100%;
    height: 800px;
    position: relative;
    background-color: black;
  }
  
  .lastdiv{
    max-width: 1400px;
    margin-left: auto;
    margin-right: auto;
  }
  
  @media screen and (max-width: 480px) {
    .finaldiv {
      width: 100%;
      height: 735px;
      position: relative;
      background-color: #00207E;
      top:25px;
    }
  }
  
  .picasso {
    width: 20%;
    top: 230px;
    left: 50px;
    position: relative;
  }
  
  @media screen and (max-width: 480px) {
    .picasso {
      width: 35%;
      top: 350px;
      left: 50px;
      position: relative;
    }
  }
  
  .picasso2 {
    width: 20%;
    top: 230px;
    left: 50px;
    position: relative;
  }
  
  @media screen and (max-width: 480px) {
    .picasso2 {
      width: 35%;
      top: 350px;
      left: 50px;
      position: relative;
    }
  }
  
  
  .end {
    display: -webkit-inline-box;
    position: relative;
    left: 35%;
    margin-top: 200px;
  }
  
  @media screen and (max-width: 480px) {
    .end {
      display: block;
      position: relative;
      top: 55px;
      align-items: center;
      text-align: center;
      width: 35%;
    }
  }
  
  .end1 {
    width: 100px;
    height: 55px;
    background-color: white;
    border-radius: 5px;
    text-align: center;
    margin: 20px;
  }
  
  @media screen and (max-width: 480px) {
    .end1 {
      width: 85px;
      height: 45px;
      background-color: white;
      border-radius: 5px;
      text-align: center;
      margin: 20px;
    }
  }
  
  .end1:hover {
  background-color: #00C0FF;
  }
  
  .end2 {
    width: 100px;
  height: 55px;
  background-color: white;
  border-radius: 5px;
  text-align: center;
  margin: 20px;
  }
  
  @media screen and (max-width: 480px) {
    .end2 {
      width: 85px;
      height: 45px;
      background-color: white;
      border-radius: 5px;
      text-align: center;
      margin: 20px;
    }
  }
  
  .end2:hover {
  background-color: #00C0FF;
  }
  
  .end3 {
    width: 100px;
    height: 55px;
    background-color: white;
    border-radius: 5px;
    text-align: center;
    margin: 20px;
  }
  
  .end3:hover {
  background-color: #00C0FF;
  }
  
  .end4 {
    width: 100px;
    height: 55px;
    background-color: white;
    border-radius: 5px;
    text-align: center;
    margin: 20px;
  }
  
  .end4:hover {
  background-color: #00C0FF;
  }
  
  @media screen and (max-width: 480px) {
    .end3 {
      width: 85px;
      height: 45px;
      background-color: white;
      border-radius: 5px;
      text-align: center;
      margin: 20px;
    }
  }
  
  @media screen and (max-width: 480px) {
    .end4 {
      width: 85px;
      height: 45px;
      background-color: white;
      border-radius: 5px;
      text-align: center;
      margin: 20px;
    }
  }
  
  .final {
    position: relative;
    color: #00207E;
    text-align: center;
    font-size: 18px;
    font-weight: 800;
    letter-spacing: -1px;
    line-height: 1;
    padding-top: 2px;
  }
  
  @media screen and (max-width: 480px) {
    .final {
      position: relative;
      color: #00207E;
      text-align: center;
      font-size: 13px;
      font-weight: 800;
      letter-spacing: -1px;
      line-height: 1;
      top: -27px;
    }
  }

  
  .ultimateCenteredBoth {
    display:flex;
    justify-content:center;
    align-items:center;
  }
  
  .melo {
  width:50%;
  margin-left:100px;
  }
  
  .bottomright
  {
  width: 200px;
  height: 70px;
  position: relative;
  top: 120px;
  left: 70%;
  }
  
  .skillsGeneral{
    transform: translate3d(0px, 0px, 0px);
  }
  @media screen and (max-width: 480px) {
    .bottomright {
      width: 115px;
      height: 70px;
      position: absolute;
      bottom: 20px;
      left: 50%;
      top: 85%;
    }
  }
  
  .name {
    position: relative;
    color: white;
    text-align: center;
    font-size: 30px;
    font-weight: 600;
    letter-spacing: -1px;
    line-height: 1;
  }

    
  .name:hover {
  /* letter-spacing: 2px; */
  }
  
  @media screen and (max-width: 480px) {
    .name {
      position: relative;
      color: white;
      text-align: center;
      font-size: 20px;
      font-weight: 600;
      letter-spacing: -1px;
      line-height: 1;
    }
  }

    .worknstudy {
    position: relative;
    top: 200px;
    color: white;
    text-align: center;
    font-size: 50px;
    font-weight: 600;
    letter-spacing: -2px;
    line-height: 1;
  }
</style>