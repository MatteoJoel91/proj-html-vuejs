<template>
  <section class="container">
        <div class="row ms-padding ms-altezza-sezione justify-content-center text-center">
            <div class="col-10 ms-style">
                <h6 class="mb-4">INTRODUCTION VIDEO</h6>
                <span>Advisory</span> <span class="testo-2 rounded-3 ms-2">Performance</span>
                <h5 class="my-4">Financial executives need to review their strategies, operating models 
                    and capabilities so that their arenas can generate sound information 
                    for better decision making.
                </h5>
                <div class="hover">
                    <img class="img-fluid test rounded-3" src="../../assets/img/video-1.jpg" alt="">
                    <div class="img-hover rounded-3 d-flex justify-content-center align-items-center">
                        <i class="fa-solid fa-play"></i>
                    </div>
                </div>
                
            </div>
        </div>
  </section>
</template>

<script>
export default {
    name: 'SectionVideo'
}
</script>

<style lang="scss">

    @import "../../assets/style/variabili.scss";

    .img-hover{
        background-color: $colorOpacity1;
        position: absolute;
        top: 0;
        right: 0;
        bottom: 0;
        left: 0;
        width: 100%;
        height: auto;
        color: $colorOpacity2;
        font-size: 100px;
    }
    .hover{
        position: relative;
    }
</style>