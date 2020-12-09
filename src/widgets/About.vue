<template>
    <div id="about" class="full-height secondary-bg">
       <b-container fluid>
           <b-row id="work1">
               <b-container>
                   <b-row id="work1row">
                        <b-col cols="12" class="">
                            <h3 class="subHeading pt-3">
                               How Wash Hub <span class="primary-color">Works</span>
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
                                <b-img :src="require('@/assets/deliver.svg')"  class="aboutIcon" fluid alt="icon" ></b-img>
                            </b-avatar>
                            <p class="desc pt-3">
                                <span class="descHead">We Deliver</span> -
                                Your clothes are dropped off clean and ready to wear
                            </p>
                        </b-col>
                   </b-row>
               </b-container>
           </b-row>
           <b-row id="work2">
               <b-container>
                   <b-row id="work2row">
                        <b-col cols="12" class="">
                            <h3 class="subHeading pt-4">
                               Clean Clothes, <span class="primary-color">Y'all!</span>
                            </h3>
                            <!-- <p class="headingDesc">Save time and money with free pickup and delivery to your home or office</p> -->
                        </b-col>
                        <b-col class="pt-4">
                            <b-avatar size="5rem" class="aboutAv">
                                <b-img :src="require('@/assets/schedule.svg')"  class="aboutIcon" fluid alt="icon" ></b-img>
                            </b-avatar>
                            <p class="descHead">Schedule a Pickup</p>
                            <p class="desc pt-3">
                                Choose pickup and delivery days
                            </p>
                        </b-col>
                        <b-col class="pt-4">
                            <b-avatar size="5rem" class="aboutAv">
                                <b-img :src="require('@/assets/pickup.svg')"  class="aboutIcon" fluid alt="icon" ></b-img>
                            </b-avatar>
                            <p class="desc pt-3">
                                <span class="descHead">We Pickup</span> -
                                Wash Hub delivery driver picks up your order
                            </p>
                        </b-col>
                        <b-col class="pt-4">
                            <b-avatar size="5rem" class="aboutAv">
                                <b-img :src="require('@/assets/deliver.svg')"  class="aboutIcon" fluid alt="icon" ></b-img>
                            </b-avatar>
                            <p class="desc pt-3">
                                <span class="descHead">We Deliver</span> -
                                Your clothes are dropped off clean and ready to wear
                            </p>
                        </b-col>
                   </b-row>
               </b-container>
           </b-row>
       </b-container>
     </div>
</template>

<script>
export default {
    name: "About",
}
</script>

<style scoped>
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
</style>