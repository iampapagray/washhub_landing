<template>
    <div id="hero" class="full-height secondary-bg">
       <div id="mainHero" class="hero-height primary-bg">
         <b-container class="pr-0">
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
            <b-col class="float-right">
              <b-img :src="require('@/assets/wash_hub_hero.png')"  class="heroImg" fluid alt="Illustration" ></b-img>
            </b-col>
          </b-row>
        </b-container>
       </div>
     </div>
</template>

<script>
export default {
    name: "Hero",
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
  .heroImg {
    position: absolute;
    right: -7px;
    top: -26.5vh;
    height: 80vh;

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