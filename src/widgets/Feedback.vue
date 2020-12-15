<template>
    <div id="feedback" class="full-height primary-bg">
       <b-container fluid>
           <b-row id="feedBack">
               <b-container>
                   <b-row class="feedBackRow">
                        jkj
                   </b-row>
               </b-container>
           </b-row>
           <b-row id="work1">
               <b-container>
                   <b-row class="feedBackRow">
                        
                   </b-row>
               </b-container>
           </b-row>
       </b-container>
     </div>
</template>

<script>
export default {
    name: "Feedback",
}
</script>

<style scoped>
    #feedBack {
        min-height: 42.5vh;
    }
    .feedBackRow {
        padding-left:5%;
        padding-right:5%;
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