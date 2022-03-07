<template>
    <!-- Sezione footer-bot con info finale -->
    <section class="ms-footer-bot d-flex align-items-center">
        <div class="container">

            <!-- Riga con 2 colonne -->
            <div class="row">

                <!-- Colonna 1 -->
                <div class="col-6">
                    <span>
                        Enjoy the low price. We are tracking 
                        any intention of piracy.
                    </span>
                </div>

                <!-- Colonna 2 -->
                <div class="col-6 text-end">
                    <span>© 2020 NEXGEN is Proudly Powered by <span class="text-color-footer-bot">Codings</span>.</span>                   
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'MyFooterBot'
}
</script>

<style lang="scss">

    @import "../../assets/style/variabili.scss";

    .ms-footer-bot{
        width: 100%;
        height: 80px;
        background-color: $colorBlack4;

        span{
            color: $colorGreyFooter;

            .text-color-footer-bot{
                color: $colorDarkTurchese;
            }
        }
    }
</style>