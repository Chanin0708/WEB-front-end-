<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <NavBar/>
    <!-- <router-view /> -->
    <Footer/>
    
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import Footer from './components/footer.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    Footer
  }
}
</script>
