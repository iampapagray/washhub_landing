<template>
    <div id="feedback" class=" primary-bg">
       <b-container fluid>
           <b-row id="feedBack">
               <b-container>
                   <b-row class="feedBackRow feedbackHeight" align-v="center">
                        <b-col cols="4" class="text-left ">
                            <div class="imageBox">
                                <b-img :src="require('@/assets/bubble.svg')"  class="bubbleIcon" fluid alt="bubble icon" ></b-img>
                            </div>
                            <div class="innerBox">
                                <h3 class="subHeading">
                                    What People Are <span class="alt-color">Saying</span>
                                </h3>
                            </div>
                            
                        </b-col>
                        <b-col cols="4" class="text-left">
                            <div class="feedBox">
                                <div class="top"></div>
                                <div class="bottom"></div>
                                <div class="content d-flex align-items-center justify-content-center">
                                    <div class="box px-1">
                                        <b-avatar size="4rem" :src="require('@/assets/person.jpg')"></b-avatar>
                                        <p class="feedbackText">
                                            Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
                                            Similique aperiam sapiente maiores quod cum officiis, 
                                            accusan suscipit sunt impedit! Vel, ratione error?
                                        </p>
                                        <b-img :src="require('@/assets/5star.svg')"  class="ratings" fluid alt="5-stars" ></b-img>
                                        <h6 class="feedbackName">
                                            Steve Smith <span class="name-alt">from Austin</span>
                                        </h6>
                                    </div>
                                </div>
                            </div>
                        </b-col>
                        <b-col cols="4" class="text-left">
                            <div class="feedBox">
                                <div class="top"></div>
                                <div class="bottom"></div>
                                <div class="content d-flex align-items-center justify-content-center">
                                    <div class="box px-1">
                                        <b-avatar size="4rem" :src="require('@/assets/person.jpg')"></b-avatar>
                                        <p class="feedbackText">
                                            Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
                                            Similique aperiam sapiente maiores quod cum officiis, 
                                            accusan suscipit sunt impedit! Vel, ratione error?
                                        </p>
                                        <b-img :src="require('@/assets/4star.svg')"  class="ratings" fluid alt="5-stars" ></b-img>
                                        <h6 class="feedbackName">
                                            Kristen Lynn <span class="name-alt">from Ohio</span>
                                        </h6>
                                    </div>
                                </div>
                            </div>
                        </b-col>
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
        min-height: 63.75vh;
    }
    .feedBox {
        height: 40vh;
        width: 70%;
        background-color: var(--deep);
        border-radius: 16px;
    }
    .top{
        height: 8vh;
    }
    .bottom{
        height: 32vh;
        width: 100%;
        background-color: white;
        border-bottom-left-radius: 16px;
        border-bottom-right-radius: 16px;
    }
    .content{
        z-index: inherit;
        text-align: center;
        position: absolute;
        top: 0;
        height: 40vh;
        width: 64%;
    }
    .feedbackText {
        padding-top: 4vh;
        font-size: 0.6rem;
    }
    .feedbackName {
        font-size: 0.7rem;
        color: var(--deep);
        font-weight: 600;
        margin-top: 1vh;
    }
    .name-alt {
        color: var(--deep);
        font-weight: 400;
    }
    .ratings {
        width:40%;
        margin-top: 3vh;
    }
    .feedBackRow {
        padding-left:5%;
        padding-right:5%;
    }
    .subHeading{
        font-weight: 700;
        color: white;
    }
    .headingDesc{
        font-weight: 600;
        color: var(--grey);
    }
    .innerBox {
        width: 60%;
        margin-left: 20%;
    }
    .imageBox{
        width: 18%;
        margin-left: 65%;
        align-items: flex-end;
        justify-content: end;
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
    .feedbackHeight {
        min-height: 63.75vh;
    }
    .bubbleIcon {
        height: 80px;
        width: 80px;
    }
</style>