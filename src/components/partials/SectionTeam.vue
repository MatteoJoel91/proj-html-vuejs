<template>
    <!-- Sezione team divisa in 2 colonne -->
    <section class="container ms-style ms-sezione-team">
        <div class="row">
            <!-- Colonna sinistra -->
            <div class="col-7">
                <!-- Info della sezione + 4 box  -->
                <h6 class="mb-4">WE LIKE WHAT WE DO</h6>
                <span class="testo-2 rounded-3 me-2">Team</span> <span>of Experts</span>
                <h5 class="my-5">Ethics and integrity are the bases on which our professionals build theyr 
                    careers. They are fundamentals that become daily attitudes.
                </h5>
                <div class="row">
                    <!-- Tutti i box sono divisi in 2 colonne con a sinistra l'immagine ed a destra le varie info -->
                    <!-- Box 1 -->
                    <div class="col-6 mb-5">
                        <div class="row">
                            <div class="col-4">
                                <img class="img-fluid rounded-3" src="../../assets/img/team-1.jpg" alt="">
                            </div>
                            <div class="col-8">
                                <h4>David Cooper</h4>
                                <h5>CTO & CO-FOUNDER</h5>
                                <i class="fa-brands fa-facebook-f icon-team-f me-2"></i>
                                <i class="fa-brands fa-twitter icon-team me-2"></i>
                                <i class="fa-brands fa-linkedin-in icon-team"></i>
                            </div>                              
                        </div>                      
                    </div>

                    <!-- Box 2 -->
                    <div class="col-6 mb-5">
                        <div class="row">
                            <div class="col-4">
                                <img class="img-fluid rounded-3" src="../../assets/img/team-3.jpg" alt="">
                            </div>
                            <div class="col-8">
                                <h4>Oliver Jones</h4>
                                <h5>CHIEF PROCUREMENT</h5>
                                <i class="fa-brands fa-facebook-f icon-team-f me-2"></i>
                                <i class="fa-brands fa-twitter icon-team me-2"></i>
                                <i class="fa-brands fa-linkedin-in icon-team"></i>
                            </div>                              
                        </div>
                    </div>

                    <!-- Box 3 -->
                    <div class="col-6">
                        <div class="row">
                            <div class="col-4">
                                <img class="img-fluid rounded-3" src="../../assets/img/team-2.jpg" alt="">
                            </div>
                            <div class="col-8">
                                <h4>Emma Lopez</h4>
                                <h5>CHIEF MARKETING</h5>
                                <i class="fa-brands fa-facebook-f icon-team-f me-2"></i>
                                <i class="fa-brands fa-twitter icon-team me-2"></i>
                                <i class="fa-brands fa-linkedin-in icon-team"></i>
                            </div>                              
                        </div>                      
                    </div>

                    <!-- Box 4 -->
                    <div class="col-6">
                        <div class="row">
                            <div class="col-4">
                                <img class="img-fluid rounded-3" src="../../assets/img/team-4.jpg" alt="">
                            </div>
                            <div class="col-8">
                                <h4>T. Johnson</h4>
                                <h5>CEO & PRESIDENT</h5>
                                <i class="fa-brands fa-facebook-f icon-team-f me-2"></i>
                                <i class="fa-brands fa-twitter icon-team me-2"></i>
                                <i class="fa-brands fa-linkedin-in icon-team"></i>
                            </div>                              
                        </div>                      
                    </div>
                </div>
            </div>

            <!-- Colonna destra -->
            <div class="col-5 d-flex align-items-end">
                <div class="box-paragrafo rounded-3">
                    <h3>President Speech</h3>
                    <p>
                        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Asperiores atque repellendus ratione soluta numquam facere, 
                        quis molestias impedit, error mollitia non natus doloribus tempora sint labore porro quo voluptatibus dignissimos.
                    </p>
                    <p>
                        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Non cum ab officia. Ratione nisi dolor id iste veniam corporis 
                        numquam optio fugiat, inventore dignissimos officia ab commodi ut eos in.
                    </p>
                    <p>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Ea error impedit similique sint non velit! Suscipit alias magnam, 
                        sunt laboriosam quis molestiae ab aliquid sint odio a officiis incidunt sit?
                    </p>
                    <p>T. Johnson</p>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'SectionTeam'
}
</script>

<style lang="scss">

    @import "../../assets/style/variabili.scss";

    .ms-sezione-team{
        margin: 80px 0px;
        height: 600px;

        h5{
            font-size: 15px;
        }

        .icon-team-f{
            padding: 10px 13px;
            background-color: $colorDoubleLightGrey;
            color: $colorDarkTurchese;
            border-radius: 50%;
        }

        .icon-team{
            padding: 10px 10px;
            background-color: $colorDoubleLightGrey;
            color: $colorDarkTurchese;
            border-radius: 50%;
        }

        .box-paragrafo{
            width: 100%;
            height: 85%;
            background-color: $colorDarkTurchese;
            padding: 30px;
            color: $colorWhite;
        }
    }
</style>