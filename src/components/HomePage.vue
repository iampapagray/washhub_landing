<template>
  <div class="container-fluid m-0 p-0">
     <nav-bar></nav-bar>

     <hero></hero>

     <about></about>
     
     <div id="features" class="bg-info">Features</div>
     <div id="featured" class="bg-danger">Featured Service</div>
     <div id="featuredPricing" class="bg-success">Featured Pricing</div>
     <div id="feedback" class="bg-warning">Feedback</div>
     <div id="contact" class="bg-info">Contact</div>
     <div id="footer" class="bg-danger">Footer</div>
 </div>
</template>

<script>
import About from '../widgets/About.vue'
import Hero from '../widgets/Hero.vue'
import NavBar from '../widgets/NavBar.vue'
export default {
  name: 'HomePage',
  components: {
    NavBar,
    Hero,
    About
  },
  data () {
    return {
      
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
 
</style>
