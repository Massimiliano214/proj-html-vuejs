<script>
    export default {
        name: "FooterBottom"
    }
</script>

<template>
    <div class="container-fluid py-4 position-relative">
        <div class="container d-flex justify-content-between">
            <div class="divider">
                <span>Enjoy the low price. We are tracking any intention of piracy.</span>
            </div>

            <div class="divider">
                <i class="px-2 fa-regular fa-copyright"></i>
                <span>2020 NEXGEN is Proudly Powered by <span class="myColor">Codings</span>.</span>    
            </div>
            
        </div>

        <div class="arrowUp">
            
            <a href="#"><i class="fa-solid fa-arrow-up"></i></a>
        </div>
        
    </div>

</template>


<style scoped lang="scss">
    @import "../styles/general.scss";

    .container-fluid {
        background-color: $cube-black;

        .container {
            color: $cube-lightGray;

            .myColor {
                color: $cube-lightGreen;
            }
        }

        .arrowUp {
            position: absolute;
            top: 24px;
            right: 40px;

            a {
                text-decoration: none;
                color: $cut-black;
                background-color: rgba($cube-white, $alpha: 0.2);
                padding: 15px 20px;
                border-radius: 50%;

                * {
                    font-size: 1.2rem;
                }
            }
        }
    }
</style>