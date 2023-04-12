<script>
    export default {
        name: "FooterBottom"
    }
</script>

<template>
    <div class="container-fluid py-4">
        <div class="container d-flex justify-content-between">
            <div class="divider">
                <span>Enjoy the low price. We are tracking any intention of piracy.</span>
            </div>

            <div class="divider">
                <i class="px-2 fa-regular fa-copyright"></i>
                <span>2020 NEXGEN is Proudly Powered by <span class="myColor">Codings</span>.</span>    
            </div>
            
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
    }
</style>