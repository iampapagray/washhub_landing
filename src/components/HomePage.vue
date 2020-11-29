<template>
  <div class="container-fluid m-0 p-0">
     <nav-bar></nav-bar>
     <div id="hero" class="full-height secondary-bg">
       <div id="mainHero" class="hero-height primary-bg">
         <b-container >
          <b-row align-v="center" class="pt-4">
            <b-col class="text-left">
              <p class="secondary-color heroText">
                Laundry & dry cleaning picked up and delivered to 
                <span class="alt-color">your door</span>
              </p>
              <p class="heroDesc">
                Hassle-free and affordable dry cleaning and 
                laundry delivered to your home or office
              </p>
              <b-button id="heroAction" pill>Schedule A Pickup</b-button>
            </b-col>
            <b-col>2 of 2</b-col>
          </b-row>
        </b-container>
       </div>
     </div>

     <div id="about" class="bg-success">How it works</div>
     <div id="features" class="bg-info">Features</div>
     <div id="featured" class="bg-danger">Featured Service</div>
     <div id="featuredPricing" class="bg-success">Featured Pricing</div>
     <div id="feedback" class="bg-warning">Feedback</div>
     <div id="contact" class="bg-info">Contact</div>
     <div id="footer" class="bg-danger">Footer</div>
 </div>
</template>

<script>
import NavBar from '../widgets/NavBar.vue'
export default {
  name: 'HomePage',
  components: {
    NavBar
  },
  data () {
    return {
      
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .heroText{
    font-weight: 800;
    font-size: 2.5em;
    width:40vw;
  }
  .heroDesc {
    font-weight: 800;
    color: var(--whisper);
    width:35vw;
  }
  #heroAction {
    text-transform: uppercase;
    font-weight: 800;
    background-color: var(--pink);
    color: var(--deep);
    padding: 15px 30px;
    font-size: 0.8rem;
    letter-spacing: 2px;
  }
  #mainHero {
    padding-left:5%;
  }
</style>
