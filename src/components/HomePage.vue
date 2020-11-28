<template>
 <div class="container-fluid m-0 p-0">
     <!-- <div id="navbar" class="nav-height primary-bg">
       <div class="container">
           <nav class="col">
              <div class="logoArea">

              </div>
              
           </nav>
       </div>
     </div> -->
     <nav-bar></nav-bar>
     <div id="hero" class="full-height secondary-bg">
       <div id="mainHero" class="hero-height primary-bgs">
         Main Hero
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
  #navbar {
    display: flex;
    width: 100%;
    align-items: center;
    /* justify-content: center; */
  }
  ul {
    display: flex;
    list-style: none;
    /* padding: 0; */
    /* margin: 0 20px 0 0; */
  }
  li {
    font-size: 1.2rem;
    /* padding: 10px 10px; */
    cursor: pointer;
    color: var(--whisper);
  }
  li:hover {
    font-size: 1.2rem;
    padding: auto 10px;
    cursor: pointer;
    color:var(--pink);
    }
  .nav{
    /* position: absolute;
    top: 7% !important; */
  }
</style>
