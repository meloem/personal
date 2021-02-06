<template>
  <div id="app">

    <div class="scroll">
    <div class="container">
      <div class="largeScreen centre">
      <Slider/>
      <Stars/>
      <Language/>
      <Renard/>
      <Bottom/>
    </div>  
    </div>
      <Yellowdiv/>
      <Map/>
      <Like/>
      <Previous/>
      <Skills/>
      <Final/>

    </div>
  </div>
</template>

<script>
import './main.css'
import Slider from './components/Slider'
import Language from './components/Language'
import Renard from './components/Renard'
import Bottom from './components/Bottom'
import Stars from './components/Stars'
import Yellowdiv from './components/Yellowdiv'
import Map from './components/Map'
import Like from './components/Like'
import Previous from './components/Previous'
import Skills from './components/Skills'
import Final from './components/Final'


export default {
  name: 'App',
  components: {
  Slider,
  Language,
  Renard,
  Bottom,
  Stars,
  Yellowdiv,
  Map,
  Like,
  Previous,
  Skills,
  Final,
  },
}
</script>