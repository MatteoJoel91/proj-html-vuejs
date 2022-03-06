<template>
    <div>
        <section class="ms-footer-top ms-padding d-flex align-items-center">
            <div class="container">
                <div class="row">
                    <div class="col-3 text-color-footer-top">
                        <img class="logo-img-fluid mb-4" src="../assets/img/nexgen-logo.svg" alt="">
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
                    <div class="col-3 d-flex justify-content-center p-0">
                        <div class="box-footer-top">
                            <h3 class="mb-4">About</h3>
                            <ul>
                                <li><i class="fa-solid fa-chevron-right me-3"></i><a href="#">The Company</a></li>
                                <li><i class="fa-solid fa-chevron-right me-3"></i><a href="#">Istitutional</a></li>
                                <li><i class="fa-solid fa-chevron-right me-3"></i><a href="#">Social & Event</a></li>
                                <li><i class="fa-solid fa-chevron-right me-3"></i><a href="#">Innovation</a></li>
                                <li><i class="fa-solid fa-chevron-right me-3"></i><a href="#">Environment</a></li>
                                <li><i class="fa-solid fa-chevron-right me-3"></i><a href="#">Technology</a></li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-3 d-flex justify-content-center p-0">
                        <div class="box-footer-top">
                            <h3 class="mb-4">Services</h3>
                            <ul>
                                <li><i class="fa-solid fa-chevron-right me-3"></i><a href="#">Audit & Assurance</a></li>
                                <li><i class="fa-solid fa-chevron-right me-3"></i><a href="#">Financial Advisory</a></li>
                                <li><i class="fa-solid fa-chevron-right me-3"></i><a href="#">Analytics M&A</a></li>
                                <li><i class="fa-solid fa-chevron-right me-3"></i><a href="#">Middle Marketing</a></li>
                                <li><i class="fa-solid fa-chevron-right me-3"></i><a href="#">Legal Consulting</a></li>
                                <li><i class="fa-solid fa-chevron-right me-3"></i><a href="#">Regulatory Risk</a></li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-3 d-flex justify-content-center p-0">
                        <div class="box-footer-top">
                            <h3 class="mb-4">Support</h3>
                            <ul>
                                <li><i class="fa-solid fa-chevron-right me-3"></i><a href="#">Responsibility</a></li>
                                <li><i class="fa-solid fa-chevron-right me-3"></i><a href="#">Terms of Use</a></li>
                                <li><i class="fa-solid fa-chevron-right me-3"></i><a href="#">About Cookies</a></li>
                                <li><i class="fa-solid fa-chevron-right me-3"></i><a href="#">Privacy Policy</a></li>
                                <li><i class="fa-solid fa-chevron-right me-3"></i><a href="#">Accessibility</a></li>
                                <li><i class="fa-solid fa-chevron-right me-3"></i><a href="#">Information</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="ms-footer-bot d-flex align-items-center">
            <div class="container">
                <div class="row">
                    <div class="col-6">
                        <span>
                            Enjoy the low price. We are tracking 
                            any intention of piracy.
                        </span>
                    </div>
                    <div class="col-6 text-end">
                        <span>© 2020 NEXGEN is Proudly Powered by <span class="text-color-footer-bot">Codings</span>.</span>                   
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
export default {
    name: 'MyFooter',
}
</script>

<style lang="scss">
    .ms-footer-top{
        width: 100%;
        height: 600px;
        background-image: url('../assets/img/bg-7.jpg');
        background-position: center;
        background-repeat: no-repeat;

        .logo-img-fluid{
            width: 50%;
        }

        .text-color-footer-top{
            color: #a2a9af;
        }

        .box-footer-top{
            width: 80%;
            height: 100%;
            padding: 30px;
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 10px;

            h3{
                color: white;
            }

            ul{
                padding: 0;
            }

            ul li{
                list-style: none;
                color: #a2a9af;
                margin: 10px 0px;

                a{
                    text-decoration: none;
                    color: #a2a9af;

                    &:hover{
                        text-decoration: underline;
                    }
                }
            }
        }
    }

    .ms-footer-bot{
        width: 100%;
        height: 80px;
        background-color: #060a0c;

        span{
            color: #a2a9af;

            .text-color-footer-bot{
                color: #058283;
            }
        }
    }
</style>