<template>
  <div id="app">
    <header-bar />
    <div class="content">
      <hello-world msg="Welcome to Your Vue.js App"/>
      <hello-world msg="Welcome to Your Vue.js App"/>
    </div>

    <footer-bar />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import HeaderBar from './components/layout/Header.vue'
import FooterBar from './components/layout/Footer.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    HeaderBar,
    FooterBar
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  display: flex;
  position: relative;
  flex-direction: column;
  min-height: 100vh;


}

.content{
  display: flex;
  height: 100%;
  position: relative;
  -moz-box-flex: 1;
  -webkit-flex: 1;
  -moz-flex: 1;
  -ms-flex: 1;
  flex: 1;
}
</style>
