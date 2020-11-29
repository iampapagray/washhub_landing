<template>
    <b-navbar id="navBar" toggleable="md" type="dark"  class="primary-bg nav-height">
        <b-container class="">
           <b-navbar-brand>
                <a class="navbar-brand" href="#">
                    <b-img class="logo" :src="require('@/assets/logo3.png')" fluid alt="Logo"></b-img>
                </a>
            </b-navbar-brand>

            <b-navbar-toggle target="navBarMenu"></b-navbar-toggle>
            
            <b-collapse class="collapse navbar-collapse" id="navBarMenu" is-nav>
                <b-navbar-nav class="ml-auto">
                    <li class="nav-item"><a class="nav-link" href="#">Wash & Fold</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Dry Cleaning</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Pricing</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
                    <!-- <li class="nav-item"><a class="nav-link" href="#">Schedule Pickup</a></li> -->
                    <b-button class="nav-link alt-bg" size="sm" pill>Schedule Pickup</b-button>
                </b-navbar-nav>
            </b-collapse>
        </b-container>
    </b-navbar>
</template>

<script>
export default {
    name: "NavBar",
}
</script>

<style scoped>
    #navBar {
        padding-left:6%;
        padding-right:6%;
    }
    img.logo {
        height: 8vh;
        width: 15vw;
    }
    .nav-link {
        text-transform: uppercase !important;
        font-size: 0.7rem;
        font-weight: 800;
        color: var(--whisper) !important;
    }
    button.btn.nav-link {
        color: var(--deep) !important;
        align-items: center;
        justify-content: center;
        font-size: 0.7rem;
        padding-left: 30px !important;
        padding-right:30px !important;
    }
    button.btn.nav-link:hover{
        color: var(--deep) !important;
        align-items: center;
        justify-content: center;
        font-size: 0.7rem;
        padding-left: 30px;
        padding-right:30px;
        background-color: var(--pink) !important;
    }

    @media (min-width: 768px){
        .navbar-expand-md .navbar-nav .nav-link {
            padding-right: 1.2rem;
            padding-left: 1.2rem;
        }
    }


</style>