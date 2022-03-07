<template>
  <section class="ms-container-doing">
        <div class="container">
            <div class="row ms-padding justify-content-center text-center">
                <div class="col-10 ms-style">
                    <h6 class="mb-4">WHAT ARE WE DOING</h6>
                    <span class="ms-testo-background rounded-3 me-2">Results</span> <span>in Numbers</span>                 
                </div>
            </div>
            <div class="row text-light text-center ms-results">
                <div class="col-3">
                    <h2>128</h2>
                    <h4>Certifications</h4>
                </div>
                <div class="col-3">
                    <h2>230</h2>
                    <h4>Employees</h4>
                </div>
                <div class="col-3">
                    <h2>517</h2>
                    <h4>Customers</h4>
                </div>
                <div class="col-3">
                    <h2>94</h2>
                    <h4>Countries Served</h4>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'SectionDoing'
}
</script>

<style lang="scss">

    @import "../../assets/style/variabili.scss";

    .ms-container-doing{
        background-image: url('../../assets/img/bg-1.jpg');
        width: 100%;
        height: 500px;
        background-position: center;

        span{
            color: white;
        }
        .ms-results{
            h2{
                color: $colorTurchese;
                font-weight: 800;
            }
        }
    }
</style>