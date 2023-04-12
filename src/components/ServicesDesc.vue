<script>

    import CardService from './CardService.vue';

    export default {
        name: "ServicesDesc",

        components: {
            CardService
        }
    }
</script>

<template>
    <div class="container-fluid py-5">
        <div class="container">
            <h5 class="bold">ROAD TRANSPORT</h5>
            <h2 class="bold text-white py-4">Main <mark>Services</mark></h2>

            <div class="doubleDivision d-flex">
                <p>With all of this expertise and capability comes an unrivalled commitment to customer service. We will work hard to understand your needs in order to develop a productive, long.term partnership.</p>
                <div class="d-flex flex-grow-1 justify-content-end align-items-end">
                    <a href="#">SEE ALL</a>

                </div>

            </div>

            <CardService />
        </div>

    </div>
    
</template>


<style scoped lang="scss">
    @import "../styles/general.scss";
    .container-fluid {
        background-color: $cut-black;
    }
    
    .container {
        color: $cube-darkGreen;

        .bold {
            font-weight: bolder;
        }
        mark {
            color: white;
            background-color: rgba($color: $cube-darkGreen, $alpha: 0.2);


        }
        .doubleDivision {

            p {
                width: 80%;
                color: $cube-white;
                margin-bottom: 0;
            }
            
            a {
                text-decoration: none;
                color: white;
                border: 1px solid $cube-darkGreen;
                padding: 7px 20px;
                border-radius: 4px;
            }

            a:hover {
                background-color: $cube-mustard;
            }
        }
    }
</style>