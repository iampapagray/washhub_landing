<template>
  <div class="container-fluid m-0 p-0">
     <nav-bar></nav-bar>

     <hero></hero>

     <about></about>
     
     <featured></featured>

    <featured-details></featured-details>

    <feedback></feedback>
    
     <div id="contact" class="bg-info">Contact</div>
     <div id="footer" class="bg-danger">Footer</div>
 </div>
</template>

<script>
import About from '../widgets/About.vue'
import Featured from '../widgets/Featured.vue'
import FeaturedDetails from '../widgets/FeaturedDetails.vue'
import Feedback from '../widgets/Feedback.vue'
import Hero from '../widgets/Hero.vue'
import NavBar from '../widgets/NavBar.vue'
export default {
  name: 'HomePage',
  components: {
    NavBar,
    Hero,
    About,
    Featured,
    FeaturedDetails,
    Feedback
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
