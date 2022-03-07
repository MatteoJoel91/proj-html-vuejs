<template>
  <div class="ms-top-header">
      <div class="container">
            <div class="row ms-altezza align-items-center">
                <!-- Parte sinistra -->
                <div class="col-6">
                    <i class="fa-solid fa-clock me-1"></i>
                    <span> 
                        Open Hours: Mon - Sat - 9:00-18:00
                    </span>
                </div>

                <!-- Parte destra -->
                <div class="col-6 text-end">
                    <i class="fa-solid fa-phone me-1"></i>
                    <span>
                        +1 (305) 1234-5678
                    </span>
                    <i class="fa-solid fa-envelope ms-4 me-1"></i>
                    <span>
                        hello@example.com
                    </span>
                    <i class="fa-brands fa-facebook-f ms-4 me-4"></i>
                    <i class="fa-brands fa-twitter me-4"></i>
                    <i class="fa-brands fa-linkedin-in"></i>
                </div>
            </div>
        </div>
  </div>
</template>

<script>
export default {
    name: 'MyHeaderTop'
}
</script>

<style  lang="scss">

 @import "../../assets/style/variabili.scss";

    .ms-top-header{
        width: 100%;
        background-color: $colorDarkBlue;
        color: $colorLightGrey;  
    }
</style>