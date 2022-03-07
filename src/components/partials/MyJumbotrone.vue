<template>
    <!-- Background del jumbotrone inserito nella classe ms-bot-header -->
    <div class="ms-bot-header">
        <div class="container">
            <!-- Inizio Nav-bar -->
            <nav>
                <div class="row ms-altezza align-items-center pt-3">
                    <!-- Parte sinistra della Nav con Logo -->
                    <div class="col-6 logo align-items-center">
                        <img class="logo-img-fluid mb-4" src="../../assets/img/nexgen-logo.svg" alt="">
                    </div>
                    <!-- Parte destra della Nav con menù -->
                    <div class="col-6 align-items-center text-end">
                        <ul>
                            <!-- lista creata dinamicamente -->
                            <li v-for="(link, index) in links" :key="index">
                                <a class="p-3" :href="link.url">{{link.text}}</a>
                            </li>
                            <i class="fa-regular fa-user px-3"></i>
                            <button class="ms-button">GET IN TOUCH</button>
                        </ul>
                    </div> 
                </div>
            </nav>
            <!-- Fine Nav-bar -->
        </div>
        <!-- Parte centrale del jumbotrone con testo e bottoni -->
        <div class="container">
            <div class="row ms-altezza-sezione align-items-center justify-content-center text-center">
                <div class="col-7">
                    <h1 class="ms-text">Financial Risk</h1>
                    <h5 class="my-5 text-white-50">The right aoutcomes depend on continuous rigor in governance, models, 
                        and processes across the finance function.
                    </h5>
                    <button class="ms-button me-4">GET IN TOUCH</button>
                    <button class="ms-button-transp">READ MORE</button>
                </div>
            </div>   
        </div>
    </div>
</template>

<script>
export default {
    name: 'MyJumbotrone',

    data(){
    return{
      links:[
        {
          "text": "HOME",
          "url": "#",
          "active": false
        },
        {
          "text": "ABOUT",
          "url": "#",
          "active": false
        },
        {
          "text": "SERVICES",
          "url": "#",
          "active": false
        },
        {
          "text": "TEAM",
          "url": "#",
          "active": false
        },
        {
          "text": "BLOG",
          "url": "#",
          "active": false
        },       
      ]
    }
  }
}
</script>

<style lang="scss">

    @import "../../assets/style/variabili.scss";

    .ms-bot-header{
        background-image: url('../../assets/img/bg-2.jpg');
        background-repeat: no-repeat;
        background-size: cover;
        height: 900px;
        color: $colorWhite;
        .logo-img-fluid{
            width: 25%;
        }
        ul{
            margin-bottom: 0px;
        }
        nav ul li {
            display: inline-block;
            a{
                text-decoration: none;
                color: $colorWhite;
                font-weight: 500;
            }
        }
    }
</style>