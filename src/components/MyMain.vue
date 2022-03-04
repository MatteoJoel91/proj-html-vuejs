<template>
    <div class="container">
        <div class="row ms-padding ms-altezza-sezione justify-content-center text-center">
            <div class="col-10 ms-style">
                <h6 class="mb-4">INTRODUCTION VIDEO</h6>
                <span>Advisory</span> <span class="testo-2 rounded-3 ms-2">Performance</span>
                <h5 class="my-4">Financial executives need to review their strategies, operating models 
                    and capabilities so that their arenas can generate sound information 
                    for better decision making.
                </h5>
                <div class="hover ">
                    <img class="img-fluid test rounded-3" src="../assets/img/video-1.jpg" alt="">
                    <div class="test-img rounded-3 d-flex justify-content-center align-items-center">
                        <i class="fa-solid fa-play"></i>
                    </div>
                </div>
                
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'MyMain',
}
</script>

<style lang="scss">
    .ms-style{
        h6{
            color: #52babb;
        }
        h5{
            color: #a2a9af;
        }
        span{
            font-size: 50px;
            font-weight: 700;
        }
        .testo-2{
                color: #058283;
                padding: 5px 10px;
                background-color: #daeced;
            }
    }
    .test-img{
        background-color: rgba(4,83,83,0.3);
        position: absolute;
        top: 0;
        right: 0;
        bottom: 0;
        left: 0;
        width: 100%;
        height: auto;
        color: rgba(255, 255, 255, 0.7);
        font-size: 100px;
    }
    .hover{
    position: relative;
    }

</style>