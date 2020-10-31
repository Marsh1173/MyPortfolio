<template>
  <div id="app">
    <div id='Head'>
      <Directory/>
      <HeaderImage/>
      </div>
    <div id='content'>
      <hr class='style-two'>
      <router-view/>
      <hr class='style-one'>
    </div>
    <div id='footer'>
      <Footer/>
    </div>
  </div>
</template>

<script>
import Directory from '@/components/Directory.vue'
import HeaderImage from '@/components/HeaderImage.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    Directory,
    HeaderImage,
    Footer
  },
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}



#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

#content {
  min-height: calc(100vh - 350px);
  display: flex;
  flex-direction: column;
}
#footer {
  height: 75px;
}
hr.style-one {
    margin: 0px;
    height: 12px;
    border: 0;
    box-shadow: inset 0px -6px 12px -12px rgba(0, 0, 0, 0.5);
    margin-top: auto;
}
hr.style-two {
    margin: 0px;
    height: 24px;
    border: 0;
    box-shadow: inset 0px 12px 12px -12px rgba(0, 0, 0, 0.5);
    margin-bottom: 50px;
}
</style>
