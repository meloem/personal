<template>
      <label class="switch hidden-lg-up">
        <div class="slider">
        <input type="checkbox">
        <div class="slider round"></div>
        </div>
      </label>
</template>

<script>
    export default {
        name: 'Slider'
    }
</script>

<style scoped>
  /* The slider */
  .slider {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    -webkit-transition: .4s;
    transition: .4s;
  }
  
  
  
  .slider:before {
    position: absolute;
    content: "";
    height: 20px;
    width: 20px;
    left: 7px;
    bottom: 5px;
    background-color: white;
    -webkit-transition: .4s;
    transition: .4s;
  }
  
  @media screen and (max-width: 480px) {
    .slider:before {
      position: absolute;
      content: "";
      height: 17px;
      width: 17px;
      left: 5px;
      bottom: 4px;
      -webkit-transition: .4s;
      transition: .4s;
    }
  }
  
  input:checked + .slider {
    background-color: #F7CA18;
  }
  
  
  input:checked + .slider:before {
    -webkit-transform: translateX(26px);
    -ms-transform: translateX(26px);
    transform: translateX(46px);
  }
  
  @media screen and (max-width: 480px) {
    input:checked + .slider:before {
      -webkit-transform: translateX(10px);
      -ms-transform: translateX(10px);
      transform: translateX(18px);
    }
  }
  
  /* Rounded sliders */
  .slider.round {
    border-radius: 34px;
    background-color: #CF000F;
  }
  
  .slider.round:before {
    border-radius: 50%;
          background-color: white;
  }
</style>