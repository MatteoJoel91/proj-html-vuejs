<template>
    <!-- Sezione Newsletter con 1 riga e 2 colonne -->
    <section class="ms-sezione-newsletter d-flex align-items-center">
        <div class="container">

            <!-- Creo la riga -->
            <div class="row ms-style text-light justify-content-center">

                <!-- Colonna 1 -->
                <div class="col-5">
                    <h6 class="mb-4">NEWSLETTER</h6>
                        <span class="ms-testo-background rounded-3 me-2">Know</span> <span>First</span>
                    <div class="d-flex align-items-center">
                            <h5 class="my-4">
                                Follow closely and receive content about our company 
                                and the news of the current marchet    
                            </h5>
                    </div>
                </div>

                <!-- Colonna 2 con 2 input -->
                <div class="col-5">
                    <div class="form-floating mb-3">
                        <input type="text" class="form-control style-input" id="floatingInput" placeholder="Name">
                        <label for="floatingInput">Name</label>
                    </div>
                    <div class="form-floating">
                        <input type="email" class="form-control style-input mb-3" id="floatingPassword" placeholder="Email">
                        <label for="floatingPassword">Email</label>
                    </div>
                    <button class="ms-button">SUBSCRIBE</button>
                </div>
            </div>
        </div>   
    </section>
</template>

<script>
export default {
    name: 'SectionNewsletter'
}
</script>

<style lang="scss">

    @import "../../assets/style/variabili.scss";

    .ms-sezione-newsletter{
        width: 100%;
        height: 450px;
        background-color: $colorBlack1;

        .style-input{
            background-color: $colorBlack3 !important;
            color: $colorWhite !important;
            border: none;
        }
    }
</style>