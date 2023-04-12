<script>
    export default {
        name: "MyDescription"
    }
</script>

<template>
    <div class="container d-flex py-5">
        <div class="containerLeft">
            <h6>WHO WE ARE</h6>
            <h2>
                
                <mark class="decorations"><i class="fa-regular fa-gem"></i> Excellence</mark>
                in Transport
            </h2>

            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Expedita corrupti tempora voluptas qui omnis nobis suscipit voluptates architecto, mollitia molestias?</p>
            <p class="mb-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. A blanditiis at doloremque quas aut perferendis praesentium odio commodi, hic earum?</p>

            <div class="citation">
                <em>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Adipisci neque nisi delectus eveniet magnam exercitationem assumenda obcaecati inventore similique architecto.</em>

            </div>

            <p class="mt-4">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptates quisquam ea ratione aspernatur?</p>

            <ul>
                <li v-for="lorem in 5">Lorem ipsum dolor sit amet.</li>
            </ul>
        </div>

        <div class="containerRight px-1">
            <h4 class="pt-3">Vehicle types</h4>

            <div class="veichleSector border-bottom py-3 d-flex">
                <div class="veichleImg">
                    <img class="veichle img-fluid" src="../assets/img/truck-1.png" alt="Mezzo di trasporto">

                </div>
                <div class="veichleDesc d-flex justify-content-center flex-column">
                    <h3>Light</h3>
                    <span>Max Weight 1200Kg</span>
                </div>
                
            </div>

            <div class="veichleSector border-bottom py-3 d-flex">
                <div class="veichleImg">
                    <img class="veichle img-fluid" src="../assets/img/truck-1.png" alt="Mezzo di trasporto">

                </div>
                <div class="veichleDesc d-flex justify-content-center flex-column">
                    <h3>Medium</h3>
                    <span>Max Weight 6000Kg</span>
                </div>
                
            </div>

            <div class="veichleSector border-bottom py-3 d-flex">
                <div class="veichleImg">
                    <img class="veichle img-fluid" src="../assets/img/truck-1.png" alt="Mezzo di trasporto">

                </div>
                <div class="veichleDesc d-flex justify-content-center flex-column">
                    <h3>Heavy</h3>
                    <span>Max Weight 24000Kg</span>
                </div>
                
            </div>
        </div>
    </div>
        

</template>

<style scoped lang="scss">
    @import "../styles/general.scss";

    .containerLeft {
        color: $cube-darkGray;
        width: 65%;
        padding-right: 30px;
    }
    h6 {
        padding-top: 20px;
        color: $cube-darkGreen;
    }
    h2 {
        font-weight: bolder;
        padding: 20px 0;
        color: black;
    }
    .citation {
        padding-left: 50px;
        border-left: 5px solid ; 
        border-color: rgba($color: $cube-darkGreen, $alpha: 0.2);
        padding-top: 15px;
        padding-bottom: 15px;
    }   
    .decorations {
        color: $cube-darkGreen;
        background-color: rgba($color: $cube-darkGreen, $alpha: 0.2);
    }

    .containerRight {
        width: 35%;

        .veichleImg {
            padding-right: 20px;
        }
        .veichle {
            background-color: $design-lightGreen;
            width: 200px;
            padding: 10px;
        }
    }
</style>