<template>
  <!-- Sezione footer-top -->
  <section class="ms-footer-top ms-padding d-flex align-items-center">
      <div class="container">

          <!-- Creo una riga con 4 colonne -->
          <div class="row">

              <!-- Colonna 1 con info numero, email, posizione -->
              <div class="col-3 text-color-footer-top">
                  <img class="logo-img-fluid mb-4" src="../../assets/img/nexgen-logo.svg" alt="">
                  <h6 class="mb-4">A Functional HTML Template for Corporate & Business</h6>
                  <div class="mb-4 d-flex align-items-center">
                      <i class="fa-solid fa-phone icon-form me-2"></i>
                      <span class="form-span">+1 (305) 1234-5678</span>
                  </div>
                  <div class="mb-4 d-flex align-items-center">
                      <i class="fa-solid fa-envelope icon-form me-2"></i>
                      <span class="form-span">hello@example.com</span>
                  </div>
                  <div class="mb-4 d-flex align-items-center">
                      <i class="fa-solid fa-location-dot icon-form me-2"></i>
                      <span class="form-span">Main Avenue, 987</span>
                  </div>
                  <button class="ms-button-transp">GET IN TOUCH</button>
              </div>

              <!-- Colonna 2 con lista About -->
              <div class="col-3 d-flex justify-content-center p-0">
                  <div class="box-footer-top">
                      <h3 class="mb-4">About</h3>
                      <!-- Lista dinamica -->
                      <ul>
                          <li v-for="(linkA, index) in linksAbout" :key="index">
                              <a :href="linkA.url"><i class="fa-solid fa-chevron-right me-3"></i>{{linkA.text}}</a>
                          </li>
                      </ul>
                  </div>
              </div>

              <!-- Colonna 3 con lista Services -->
              <div class="col-3 d-flex justify-content-center p-0">
                  <div class="box-footer-top">
                      <h3 class="mb-4">Services</h3>
                      <!-- Lista dinamica -->
                      <ul>
                          <li v-for="(linkS, index) in linksServices" :key="index">
                              <a :href="linkS.url"><i class="fa-solid fa-chevron-right me-3"></i>{{linkS.text}}</a>
                          </li>
                      </ul>
                  </div>
              </div>

              <!-- Colonna 4 con lista Support -->
              <div class="col-3 d-flex justify-content-center p-0">
                  <div class="box-footer-top">
                      <h3 class="mb-4">Support</h3>
                      <!-- Lista dinamica -->
                      <ul>
                          <li v-for="(linkSup, index) in linksSupport" :key="index">
                              <a :href="linkSup.url"><i class="fa-solid fa-chevron-right me-3"></i>{{linkSup.text}}</a>
                          </li>
                      </ul>
                  </div>
              </div>
          </div>
      </div>
  </section>
</template>

<script>
export default {
    name: 'MyFooterTop',

    data(){
    return{
      linksAbout:[
        {
          "text": "The Company",
          "url": "#",
        },
        {
          "text": "Istitutional",
          "url": "#",
        },
        {
          "text": "Social & Event",
          "url": "#",
        },
        {
          "text": "Innovation",
          "url": "#",
        },
        {
          "text": "Environment",
          "url": "#",
        },
        {
          "text": "Technology",
          "url": "#",
        },    
      ],

      linksServices:[
        {
          "text": "Audit & Assurance",
          "url": "#",
        },
        {
          "text": "Financial Advisory",
          "url": "#",
        },
        {
          "text": "Analytics M&A",
          "url": "#",
        },
        {
          "text": "Middle Marketing",
          "url": "#",
        },
        {
          "text": "Legal Consulting",
          "url": "#",
        },
        {
          "text": "Regulatory Risk",
          "url": "#",
        },    
      ],

      linksSupport:[
        {
          "text": "Responsibility",
          "url": "#",
        },
        {
          "text": "Terms of Use",
          "url": "#",
        },
        {
          "text": "About Cookies",
          "url": "#",
        },
        {
          "text": "Privacy Policy",
          "url": "#",
        },
        {
          "text": "Accessibility",
          "url": "#",
        },
        {
          "text": "Information",
          "url": "#",
        },    
      ]
    }
  }
}
</script>

<style lang="scss">

    @import "../../assets/style/variabili.scss";

    .ms-footer-top{
        width: 100%;
        height: 600px;
        background-image: url('../../assets/img/bg-7.jpg');
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;

        .logo-img-fluid{
            width: 50%;
        }

        .text-color-footer-top{
            color: $colorGreyFooter;
        }

        .box-footer-top{
            width: 80%;
            height: 100%;
            padding: 30px;
            background-color: $colorOpacity5;
            border-radius: 10px;

            h3{
                color: $colorWhite;
            }

            ul{
                padding: 0;
            }

            ul li{
                list-style: none;
                color: $colorGreyFooter;
                margin: 10px 0px;

                a{
                    text-decoration: none;
                    color: $colorGreyFooter;

                    &:hover{
                        text-decoration: underline;
                    }
                }
            }
        }
    }
</style>