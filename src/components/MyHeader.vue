<template>

    <header>
        <div class="ms-top-header">
            <div class="container">
                <div class="row ms-altezza align-items-center">
                    <div class="col-6">
                        <i class="fa-solid fa-clock me-1"></i>
                        <span> 
                            Open Hours: Mon - Sat - 9:00-18:00
                        </span>
                    </div>
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
        <div class="ms-bot-header">
            <div class="container">
                <div class="row ms-altezza align-items-center pt-3">
                    <div class="col-6 logo align-items-center">
                            <span class="logo-1">NEX</span> <span class="logo-2">GEN</span>
                    </div>
                    <div class="col-6 align-items-center text-end">
                        <nav>
                            <ul>
                                <li><a class="p-3" href="#">HOME</a></li>
                                <li><a class="p-3" href="#">ABOUT</a></li>
                                <li><a class="p-3" href="#">SERVICES</a></li>
                                <li><a class="p-3" href="#">TEAM</a></li>
                                <li><a class="p-3" href="#">BLOG</a></li>
                                <i class="fa-regular fa-user px-3"></i>
                                <button class="ms-button">GET IN TOUCH</button>
                            </ul>
                        </nav>
                    </div> 
                </div>
            </div>
            <div class="container">
                <div class="row ms-altezza-jumbo align-items-center justify-content-center text-center">
                    <div class="col-7">
                        <h1 class="ms-text">Financial Risk</h1>
                        <h5 class="my-5 text-white-50">The right aoutcomes depend on continuous rigor in governance, models, 
                            and processes across the finance function.
                        </h5>
                        <button class="ms-button me-4">GET IN TOUCH</button>
                        <button class="ms-button-transp">READ MORE</button>
                    </div>
                </div>   
            </div>
        </div>
    </header>
    
</template>

<script>
export default {
    name: 'MyHeader',
}
</script>

<style lang="scss">
    .ms-top-header{
        width: 100%;
        background-color: #21333e;
        color: #bcbdbd;

        
    }

    .ms-bot-header{
        background-image: url('../assets/img/bg-2.jpg');
        height: 900px;
        color: white;
        .logo{
            font-weight: bold;
            font-size: 30px;

           .logo-1{
            color: #048383;
            }
            .logo-2{
                color: white;
            } 
        }
        ul{
            margin-bottom: 0px;
        }
        nav ul li {
            display: inline-block;
            a{
                text-decoration: none;
                color: white;
                font-weight: 500;
            }
        }
    }
</style>