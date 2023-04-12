<script>
    export default {
        name: "CardService"
    }
</script>


<template>
    <div class="cardSection py-5 d-flex justify-content-between">
        <div class="myCard position-relative p-4">
            <i class="iconDec rounded-5 fa-solid fa-truck-ramp-box"></i>
            <a href="#"><i class="arrows fa-solid fa-arrow-right"></i></a> 
            
            <h4 class="text-white py-4">Technology</h4>
            <p class="myDecorations">We are continually focussed on developing technology solutions adpted to our client's needs.</p>
        </div>

        <div class="myCard position-relative p-4">
            
            <i class="iconDec rounded-5 fa-solid fa-temperature-low"></i>
            <a href="#"><i class="arrows fa-solid fa-arrow-right"></i></a>

            <h4 class="text-white py-4">Reeder Cargo</h4>
            <p class="myDecorations">Regular and frequent monitoring from the receipt of the loaded container to final destination.</p>
        
        </div>

        <div class="myCard position-relative p-4">
            <i class="iconDec rounded-5 fa-solid fa-boxes-stacked"></i>
            <a href="#"><i class="arrows fa-solid fa-arrow-right"></i></a>

            <h4 class="text-white py-4">Dry Cargo</h4>
            <p class="myDecorations">We work with most types of dry cargo, from valuable cargo to the most dangerous requiring care.</p>
        
        </div>
    </div>
    

</template>



<style scoped lang="scss">

    @import "../styles/general.scss";

    .cardSection {
        width: 100%;

        .myCard {
            width: 30%;
            padding: 20px;
            background-color: rgba($cube-white, $alpha: 0.1);
            border-radius: 5px;

            
            .iconDec {
                font-size: 1.7rem;
                color: $cube-darkGreen;
                background-color: rgba($cube-darkGreen, $alpha: 0.1);
                padding: 20px;
                
            }
        }
    }

    .arrows {
        position: absolute;
        top: 25px;
        right: 25px;
        font-size: 1.7rem;
    }

    a {
        text-decoration: none;
        color: $cube-darkGreen;
    }

    a:hover {
        color: $cube-mustard;
    }

    .myDecorations {
        color: $cube-lightGray;
    }
    
</style>