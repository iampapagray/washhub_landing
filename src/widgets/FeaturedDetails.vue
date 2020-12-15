<template>
    <div id="featuredDetails" class="full-height secondary-bg">
       <b-container fluid>
           <b-row id="work1">
               <b-container>
                   <b-row id="work1row">
                        <b-col cols="12" class="">
                            <h3 class="subHeading pt-3">
                               How Wash &amp; Fold <span class="primary-color">Works</span>
                            </h3>
                            <p class="headingDesc">Save time and money with free pickup and delivery to your home or office</p>
                        </b-col>
                        <b-col class="pt-3">
                            <b-avatar size="5rem" class="aboutAv">
                                <b-img :src="require('@/assets/schedule.svg')"  class="aboutIcon" fluid alt="icon" ></b-img>
                            </b-avatar>
                            <p class="desc pt-3">
                                <span class="descHead">Schedule a Pickup</span> -
                                Choose pickup and delivery days
                            </p>
                        </b-col>
                        <b-col class="pt-3">
                            <b-avatar size="5rem" class="aboutAv">
                                <b-img :src="require('@/assets/pickup.svg')"  class="aboutIcon" fluid alt="icon" ></b-img>
                            </b-avatar>
                            <p class="desc pt-3">
                                <span class="descHead">We Pickup</span> -
                                Wash Hub delivery driver picks up your order
                            </p>
                        </b-col>
                        <b-col class="pt-3">
                            <b-avatar size="5rem" class="aboutAv">
                                <b-img :src="require('@/assets/washnfold.svg')"  class="aboutIcon" fluid alt="icon" ></b-img>
                            </b-avatar>
                            <p class="desc pt-3">
                                <span class="descHead">We Deliver</span> -
                                Your clothes are dropped off clean and ready to wear
                            </p>
                        </b-col>
                   </b-row>
               </b-container>
           </b-row>
           <b-row id="work1">
               <b-container>
                   <b-row align-v="center" id="work2row" class="pricingHeight">
                        <b-col class="" cols="3" offset="2">
                            <b-row class="">
                                <h3 class="subHeading pricingHead">
                                    Wash &amp; Fold <span class="primary-color">Pricing</span>
                                </h3>
                            </b-row>
                            <b-row class="">
                                <p class="descHead1">2-3 Loads (~5kg of laundry)</p>
                            </b-row>
                        </b-col>
                        <b-col cols="3" offset="2" class="">
                            <div class="mainBox">
                                <div class="bar"></div>
                                <div class="boxBody">
                                    <b-container>
                                        <b-row no-gutters align-v="center" class="boxBody">
                                            <b-col  cols="10" offset="1" class="text-left">
                                                <h3 class="priceHead primary-color">Ghc45/bag</h3>
                                                <p class="priceText">
                                                    We will wash and fold as much laundry 
                                                    as you can stuff in our bag. Do your best 
                                                    y'all
                                                </p>
                                                <p class="priceText ">
                                                    Including free pickup and delivery
                                                </p>
                                            </b-col>
                                        </b-row>
                                    </b-container>
                                </div>
                            </div>
                        </b-col>
                   </b-row>
               </b-container>
           </b-row>
       </b-container>
     </div>
</template>

<script>
export default {
    name: "FeaturedDetails",
}
</script>

<style scoped>
    .priceHead {
        font-weight: 600;
        /* color: ; */
    }
    .priceText {
        font-size: 0.6rem;
    }
    .mainBox {
        background-color: var(--greyish);
        min-height: 25vh;
        border-radius: 16px;
    }
    .bar {
        height: 3vh;
        background-color: var(--pink);
        border-top-left-radius: 16px;
        border-top-right-radius: 16px;
    }
    .boxBody {
        height: 22vh;
    }
    .aboutIcon {
        height: 40px;
        width: 40px;
    }
    .aboutAv {
         background-color: var(--greyish);
    }
    #work1 {
        min-height: 42.5vh;
        background-color: var(--whitish);
    }
    #work1row {
        padding-left:5%;
        padding-right:5%;
    }
    #work2row {
        padding-left:5%;
        padding-right:5%;
    }
    #work2 {
        min-height: 42.5vh;
        background-color: var(--greyish);
    }
    .subHeading{
        font-weight: 700;
        color: var(--deep);
    }
    .headingDesc{
        font-weight: 600;
        color: var(--grey);
    }
    .desc {
        font-weight: 600;
        font-size: 0.9rem;
        color: var(--grey);
    }
    .descHead{
        color: var(--deep);
    }
    .descHead1{
        font-size: 0.9rem;
        color: var(--deep);
        font-weight: 600;
    }
    .pricingHead {
        width: 12vw;
        text-align: left;
    }
    .pricingHeight {
        min-height: 42.5vh;
    }
</style>