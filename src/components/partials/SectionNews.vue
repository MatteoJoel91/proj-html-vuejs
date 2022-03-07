<template>
  <section class="sezione-news">
        <div class="container ms-padding">
            <div class="row justify-content-center">
                <div class="col ms-style">
                    <h6 class="mb-4">OUR EDITORIAL CONTENT</h6>
                    <span>LASTEST</span> <span class="ms-testo-background testo-2 rounded-3 ms-2">NEWS</span>
                    <div class="d-flex align-items-center mb-4">
                        <div class="col-9">
                            <h5 class="my-4">
                                Every week we publish content about what is best in the business world    
                            </h5> 
                        </div>
                        <div class="col-3 text-end">
                            <button class="ms-button">SEE ALL</button>
                        </div> 
                    </div>        
                </div>
            </div>
            <div class="row">
                <div class="col-4">
                    <div class="news-box">
                        <img class="img-fluid rounded-3" src="../../assets/img/news-1.jpg" alt="">
                        <div class="text-img d-flex align-items-end rounded-3 p-4">
                            <h3 class="text-center text-light">
                                Increasing creativity is possible for everyone
                            </h3>
                        </div>
                    </div>  
                </div>
                <div class="col-4 news-box">
                    <div class="news-box">
                        <img class="img-fluid rounded-3" src="../../assets/img/news-2.jpg" alt="">
                        <div class="text-img d-flex align-items-end rounded-3 p-4">
                            <h3 class="text-center text-light">
                                Because market research is part of the business man
                            </h3>
                        </div>
                    </div>
                </div>
                <div class="col-4 news-box">
                    <div class="news-box">
                        <img class="img-fluid rounded-3" src="../../assets/img/news-3.jpg" alt="">
                        <div class="text-img d-flex align-items-end rounded-3 p-4">
                            <h3 class="text-center text-light">
                                Working from home is now today
                            </h3>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'SectionNews'
}
</script>

<style lang="scss">

    @import "../../assets/style/variabili.scss";

    .sezione-news{
        width: 100%;
        min-height: 700px;
        background-color: $colorCream;

        .ms-img-fluid{
            width: 80%;
            height: auto;
        }

        .news-box{
            position: relative;
            
        }

        .text-img{
            width: 100%;
            height: 100%;
            position: absolute;
            background-color: $colorOpacity3;
            top: 0;
        }
    }
</style>