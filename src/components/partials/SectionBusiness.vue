<template>
    <!-- Sezione business con 6 box -->
    <section class="ms-container-business">

        <!-- Info generali della sezione del sito + bottone 'SEE ALL' -->
        <div class="container ms-padding">
            <div class="row justify-content-center">
                <div class="col ms-style text-light">
                    <h6 class="mb-4">OUR BUSINESS AREAS</h6>
                    <span>Excellence in</span> <span class="ms-testo-background rounded-3 ms-2">Services</span>
                    <div class="d-flex align-items-center">
                        <div class="col-9">
                            <h5 class="my-4">We are leaders in providing consultancy services with a set of cutting-edge 
                                technologies and a team of experienced and renowed professionals.
                                These are some options that you can hire.    
                            </h5> 
                        </div>
                        <!-- Bottone sulla destra -->
                        <div class="col-3 text-end">
                            <button class="ms-button-transp">SEE ALL</button>
                        </div> 
                    </div>        
                </div>
            </div>
            
            <div class="row text-light">
                <!-- Box 1 -->
                <div class="col-4">
                    <div class="box">
                        <div class="row">
                            <div class="col-10">
                                <i class="fa-solid fa-network-wired icon-box-style mb-4"></i>
                                <h3 class="pb-3">Audit & Assurance</h3>
                                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
                            </div>
                            <div class="col-2">
                                <i class="fa-solid fa-arrow-right icon-box-style"></i>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Box 2 -->
                <div class="col-4">
                    <div class="box">
                        <div class="row">
                            <div class="col-10">
                                <i class="fa-solid fa-briefcase icon-box-style mb-4"></i>
                                <h3 class="pb-3">Financial Advisory</h3>
                                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
                            </div>
                            <div class="col-2">
                                <i class="fa-solid fa-arrow-right icon-box-style"></i>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Box 3 -->
                <div class="col-4">
                    <div class="box">
                        <div class="row">
                            <div class="col-10">
                                <i class="fa-solid fa-square-poll-vertical icon-box-style mb-4"></i>
                                <h3 class="pb-3">Analytics and M&A</h3>
                                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
                            </div>
                            <div class="col-2">
                                <i class="fa-solid fa-arrow-right icon-box-style"></i>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Box 4 -->
                <div class="col-4">
                    <div class="box">
                        <div class="row">
                            <div class="col-10">
                                <i class="fa-solid fa-plane icon-box-style mb-4"></i>
                                <h3 class="pb-3">Middle Marketing</h3>
                                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
                            </div>
                            <div class="col-2">
                                <i class="fa-solid fa-arrow-right icon-box-style"></i>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Box 5 -->
                <div class="col-4">
                    <div class="box">
                        <div class="row">
                            <div class="col-10">
                                <i class="fa-solid fa-magnifying-glass icon-box-style mb-4"></i>
                                <h3 class="pb-3">Legal Consulting</h3>
                                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
                            </div>
                            <div class="col-2">
                                <i class="fa-solid fa-arrow-right icon-box-style"></i>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Box 6 -->
                <div class="col-4">
                    <div class="box">
                        <div class="row">
                            <div class="col-10">
                                <i class="fa-solid fa-box icon-box-style mb-4"></i>
                                <h3 class="pb-3">Regulatory Risk</h3>
                                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
                            </div>
                            <div class="col-2">
                                <i class="fa-solid fa-arrow-right icon-box-style"></i>
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
    name:'SectionBusiness'
}
</script>

<style lang="scss">

    @import "../../assets/style/variabili.scss";

    .ms-container-business{
        background-color: $colorBlack1;
        width: 100%;
        height: 950px;

        .box{
            width: 100%;
            height: 250px;
            background-color: $colorBlack2;
            margin: 12px 0px;
            padding: 40px;
            cursor: pointer;

            .fa-arrow-right{
                padding: 5px;
            }
            
            &:hover .icon-box-style{
                color: $colorWhite;
                }
            &:hover .fa-arrow-right{
                background-color: $colorTurchese;
                padding: 5px;
                border-radius: 50%;
            }
            .icon-box-style{
                color: $colorTurchese;
                font-size: 30px;

            }
        }
    }
</style>