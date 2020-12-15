<template>
    <div id="featured" class="full-height secondary-bg">
       <div id="mainFeatured" class="featured-height primary-bg">
         <b-container class="">
          <b-row align-v="center" class="featured-height">
            <b-col cols="6" class="text-left">
                <p class="secondary-color heroText">
                    Affordable <br>
                <span class="alt-color">Wash &amp; Fold</span>
                </p>
                <p class="heroDesc">
                    Hassle-free and affordable dry cleaning and 
                    laundry delivered to your home or office
                </p>
              <b-button id="heroAction" pill>Schedule A Pickup</b-button>
            </b-col>
            <b-col cols="6" class="float-right">
                <VueSlickCarousel class="featuredImgBox" v-bind="settings">
                    <b-img :src="require('@/assets/work1.png')"  class="featuredImg" fluid alt="Illustration" ></b-img>
                    <b-img :src="require('@/assets/work2.png')"  class="featuredImg" fluid alt="Illustration" ></b-img>
                    <b-img :src="require('@/assets/work3.png')"  class="featuredImg" fluid alt="Illustration" ></b-img>
                    
                </VueSlickCarousel>
              <!-- <b-img :src="require('@/assets/work3.png')"  class="featuredImg" fluid alt="Illustration" ></b-img> -->
            </b-col>
          </b-row>
        </b-container>
       </div>
    </div>
</template>

<script>
import VueSlickCarousel from 'vue-slick-carousel'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'
// optional style for arrows & dots
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
export default {
    name: "Featured",
    components: { VueSlickCarousel },
    data () {
    return {
        settings: {
            "dots": false,
            "arrows": false,
            "adaptiveHeight": true,
            // "dotsClass": "slick-dots custom-dot-class",
            "edgeFriction": 0.35,
            "infinite": true,
            "autoplay":true,
            "autoplaySpeed": 8000,
            "speed": 1000,
            "slidesToShow": 1,
            "slidesToScroll": 1,
            "fade": true,
        }
    }
  }
}
</script>

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
  /* .featuredImg {  } */
  .featuredImgBox {
      position: absolute;
      width: 40vw;
      right: -5.5vw;
      top: -23.5vh;
      height: 65vh;
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
  #mainFeatured {
    padding-left:5%;
  }
</style>