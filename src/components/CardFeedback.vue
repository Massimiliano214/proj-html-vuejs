<script>
    export default {
        name: "CardFeedback"
    }
</script>


<template>
    <div class="cardSection py-5 d-flex justify-content-between text-start">
        <div class="myCard position-relative p-4">
            <img class="logos img-fuid pb-4" src="../assets/img/logo-1.png" alt="logo azienda">
            <i class="quotationMarks fa-solid fa-quote-right"></i>

            <p class="myDecorations">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Dolores quibusdam sint blanditiis maxime iure suscipit nam veritatis porro a. Eum sequi placeat ipsum aspernatur at minima?</p>
            <p class="myDecorations">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dicta, temporibus!</p>
        </div>

        <div class="myCard position-relative p-4">
            
            <img class="logos img-fuid pb-4" src="../assets/img/logo-2.png" alt="logo azienda 2">
            <i class="quotationMarks fa-solid fa-quote-right"></i>

            <p class="myDecorations">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ea quam vero blanditiis voluptatum praesentium impedit labore aliquid illo earum aperiam dolore, inventore ab magnam similique ratione.</p>


            <p class="myDecorations">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ducimus, distinctio!</p>
        
        </div>

        <div class="myCard position-relative p-4">
            <img class="logos img-fuid pb-4" src="../assets/img/logo-3.png" alt="logo azienda 3">
            <i class="quotationMarks fa-solid fa-quote-right"></i>
            <p class="myDecorations">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nobis asperiores minima sed! Eligendi sed dignissimos, sequi est rem illo voluptate veniam magnam eos, repellendus illum deserunt.</p>
            <p class="myDecorations">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Reiciendis, repellat!</p>
        
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
            color: $cube-lightGreen;

            
            .iconDec {
                font-size: 1.7rem;
                color: $cube-darkGreen;
                background-color: rgba($cube-darkGreen, $alpha: 0.1);
                padding: 20px;
                
            }
        }
    }

    .quotationMarks {
        color: $cube-darkGray;
        position: absolute;
        bottom: 25px;
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

    .logos {
        filter: invert(100%);
    }
    
</style>