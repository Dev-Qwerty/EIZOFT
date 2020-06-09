<template>
  <div id="app">
    <vue-particles class="particle"
        color="#dedede"
        :particleOpacity="0.7"
        :particlesNumber="80"
        shapeType="star"
        :particleSize="4"
        linesColor="#dedede"
        :linesWidth="1"
        :lineLinked="false"
        :lineOpacity="0.4"
        :linesDistance="150"
        :moveSpeed="3"
        :hoverEffect="false"
        hoverMode="grab"
        :clickEffect="true"
        clickMode="push"
      >
      </vue-particles>
      <div>
        <Navbar/>
        <router-view />
      </div>
  </div>
</template>

<script>
import Navbar from './components/Navbar'

export default {
  name: 'App',
  components: {
    Navbar
  }
}
</script>

<style>
body::-webkit-scrollbar {  /*remove scroll bar in Chrome/Safari/Webkit*/
    display: none;
}
html {
scrollbar-width: none;  /*remove scrollbar in firefox*/
}

.particle {
  position: fixed;
  width: 100%;
  height: 100%;
  left: 0px;
  top: 0px;
  background: #ad5389;  /* fallback for old browsers */
  background: -webkit-linear-gradient(to top, #3c1053, #ad5389);  /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(to top, #3c1053, #ad5389); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
  z-index: -1 !important;
}
</style>
