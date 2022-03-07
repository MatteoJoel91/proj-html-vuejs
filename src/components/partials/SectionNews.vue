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
                        <div class="text-img rounded-3 p-4">
                            <div class="row mt-3 hover-top">
                                <div class="col-6 text-center">
                                    <span class="text-light">
                                        <i class="fa-regular fa-user me-1"></i>
                                        Andrea Miller
                                    </span> 
                                </div>
                                <div class="col-6 text-center">
                                    <span class="text-light">
                                        <i class="fa-regular fa-clock"></i>
                                        2 Days Ago
                                    </span> 
                                </div>
                            </div>
                            <div class="row second-text-box m-auto align-items-end">
                                <div class="col-12 text-center text-light">
                                    <h3 >
                                        Increasing creativity is possible for everyone
                                    </h3>
                                    <h5 class="mt-4 hover-bot">
                                        Lorem ipsum dolor sit amet consectetur adipisicing elit.
                                    </h5>
                                </div>
                            </div>
                            
                        </div>
                    </div>  
                </div>
                <div class="col-4">
                    <div class="news-box">
                        <img class="img-fluid rounded-3" src="../../assets/img/news-2.jpg" alt="">
                        <div class="text-img rounded-3 p-4">
                            <div class="row mt-3 hover-top">
                                <div class="col-6 text-center">
                                    <span class="text-light">
                                        <i class="fa-regular fa-user me-1"></i>
                                        Andrea Miller
                                    </span> 
                                </div>
                                <div class="col-6 text-center">
                                    <span class="text-light">
                                        <i class="fa-regular fa-clock"></i>
                                        2 Days Ago
                                    </span> 
                                </div>
                            </div>
                            <div class="row second-text-box m-auto align-items-end">
                                <div class="col-12 text-center text-light">
                                    <h3 >
                                        Because market research is part of the business plan
                                    </h3>
                                    <h5 class="mt-4 hover-bot">
                                        Lorem ipsum dolor sit amet consectetur adipisicing elit.
                                    </h5>
                                </div>
                            </div>
                            
                        </div>
                    </div>
                </div>
                <div class="col-4">
                    <div class="news-box">
                        <img class="img-fluid rounded-3" src="../../assets/img/news-3.jpg" alt="">
                        <div class="text-img rounded-3 p-4">
                            <div class="row mt-3 hover-top">
                                <div class="col-6 text-center">
                                    <span class="text-light">
                                        <i class="fa-regular fa-user me-1"></i>
                                        Andrea Miller
                                    </span> 
                                </div>
                                <div class="col-6 text-center">
                                    <span class="text-light">
                                        <i class="fa-regular fa-clock"></i>
                                        2 Days Ago
                                    </span> 
                                </div>
                            </div>
                            <div class="row second-text-box m-auto align-items-end">
                                <div class="col-12 text-center text-light">
                                    <h3 >
                                        Working from home is now a trend
                                    </h3>
                                    <h5 class="mt-4 hover-bot">
                                        Lorem ipsum dolor sit amet consectetur adipisicing elit.
                                    </h5>
                                </div>
                            </div>
                            
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

        .news-box{
            position: relative;

            &:hover .img-fluid{
               filter: blur(3px) !important; 
            }
            
        }
        .text-img{
            width: 100%;
            height: 100%;
            position: absolute;
            background-color: $colorOpacity3;
            top: 0;

            .hover-top{
                visibility: hidden;
            }

            .hover-bot{
                display: none;
            }

            &:hover .hover-top{
                visibility: visible;
            }

            &:hover .hover-bot{
                display: block;
            }
        }
        .second-text-box{
                width: 100%;
                height: 80%;
            }
    }
    
</style>