<template>
  <div id="app">
    <h3>NOT WORKING</h3>

    <picture>
      <source srcset="http://www.gstatic.com/webp/gallery/1.webp">
      <source srcset="http://www.gstatic.com/webp/gallery/1.jpg">
      <img src="http://www.gstatic.com/webp/gallery/1.jpg" alt="test image">
    </picture>

    <h3>WORKING</h3>

    <picture>
      <source srcset="http://www.gstatic.com/webp/gallery/2.webp 1x">
      <source srcset="http://www.gstatic.com/webp/gallery/2.jpg 1x">
      <img src="http://www.gstatic.com/webp/gallery/2.jpg" alt="test image">
    </picture>

  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
