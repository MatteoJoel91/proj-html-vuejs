<template>
    <section class="ms-sezione-form ms-padding">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-8 ms-style pe-5">
                    <h6 class="mb-4">SEND A MESSAGE</h6>
                    <span>Get in</span> <span class="ms-testo-background testo-2 rounded-3 ms-2">Touch</span>
                            <h5 class="my-4">
                                We will respond to your message as soon as possible    
                            </h5>                        
                    <form class="row g-3">
                        <div class="col-6">
                            <input type="text" class="form-control ms-input" placeholder="Name">
                        </div>

                        <div class="col-6">
                            <input type="email" class="form-control ms-input" placeholder="Email">
                        </div>
                                            
                        <div class="col-6">
                            <input type="tel" class="form-control ms-input" placeholder="Phone" id="phone">
                        </div>

                        <div class="col-6">
                            <select class="form-select ms-input">
                                <option selected>More info</option>
                                <option value="1">One</option>
                                <option value="2">Two</option>
                                <option value="3">Three</option>
                            </select>
                        </div>

                        <div class="col-12">
                            <textarea class="form-control ms-input" id="exampleFormControlTextarea1" rows="5" placeholder="Message"></textarea>
                        </div>

                        <div>
                            <button class="ms-button">SEND</button> 
                        </div>
                        
                    </form>
                </div>
                <div class="col-3">
                    <h4 class="mb-4">Example Inc.</h4>
                    <h6 class="mb-4 form-h6">Lorem ipsum dolor sit, amet consectetur adipisicing elit.</h6>
                    <h6 class="mb-4 form-h6">Lorem ipsum dolor sit, amet consectetur adipisicing elit.</h6>
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
                    
                    <button class="ms-button-form">VIEW MAP</button>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'SectionMessage'
}
</script>

<style lang="scss">

    @import "../../assets/style/variabili.scss";

    .ms-sezione-form{
        width: 100;
        height: 700px;

        .ms-input{
            background-color: $colorGreyForm1 !important;
            border: none;
        }

        .ms-button-form{
            color: $colorDarkTurchese;
            background-color: $colorOpacity4;
            border: solid 1px $colorDarkTurchese;
            padding: 10px 20px;
            border-radius: 5px;
        }

        .icon-form{
            padding: 10px 12px;
            background-color: $colorDoubleLightGrey;
            color: $colorDarkTurchese;
            border-radius: 50%;
            margin: 0 5px;
        }

        .form-span{
            color: $colorDarkTurchese;
        }

        .form-h6{
            color: $colorGreyForm2;
        }
        
    }
</style>