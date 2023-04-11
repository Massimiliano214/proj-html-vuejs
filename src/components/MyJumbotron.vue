<script>
    export default {
        name: "MyJumbotron",
        props: {
            navList: Array
        }
    }
</script>

<template>
    <div class="container-fluid">
        <div class="MyJumbo">
            <div class="imageFilters">
                <div class="container d-flex align-items-center justify-content-between">
                    <div class="imageCompany">
                        <img src="../assets/img/true-next-gen-performance.png" alt="">

                    </div>

                    <nav class="links">
                        <ul class="d-flex">
                            <li v-for="(link, index) in navList" :key="index"> <a href="#">{{ link }}</a> </li>
                            <li><i class="fa-regular fa-user"></i></li>
                            <button class="btn mybtn">GET IN TOUCH</button>
                        </ul>
                        
                    </nav>
                </div>


                <div class="container mainText">
                    <h6>LOGISTICS SERVICES</h6>
                    <h1 class="text-white">CARGO <br/> TRANSPORT</h1>
                    <span>Fractional or exlusive road cargo transportation to all regions, with small, medium and large vehicles.</span> <br/>
                    <button class="btn mybtn mt-5">GET IN TOUCH</button> 
                    <button class="btn mybtn mybtn2 mt-5">READ MORE</button>

                </div>
            </div>
            
        </div>
    </div>

</template>

<style scoped lang="scss">
    @import "../styles/general.scss";
    .container-fluid {
        padding: 0;
    
        .container {
            padding: 20px;
        }
        .MyJumbo {
            background-image: url("../assets/img/bg-9.jpg");
            width: 100%;
            height: 600px;
            background-position: center;

            .imageFilters {
                background-color: rgba($color: #000000, $alpha: 0.5);
                height: 100%;
            }
        }
        
    }

    .imageCompany {
        img {
            width: 70px;
            filter: invert(48%) sepia(13%) saturate(3207%) hue-rotate(130deg) brightness(95%) contrast(80%);

        }
    }

    .links {
        color: white;
        filter: none;
        ul {
            list-style-type: none;

            li {
                padding: 10px;

                a {
                    text-decoration: none;
                    color: white;
                }
            }
        }
        
    }

    .mainText {
        margin-top: 80px;
        h6 {
            color: $cube-darkGreen;
        }

        h1 {
            font-weight: bolder;
            font-size: 70px;
        }
        span {
            color: $cube-lightGray;
            font-weight: bolder;
        }
        .mybtn2 {
            background-color: transparent;
            border: 1px solid $cube-darkGreen;
        }
    }
    .mybtn {
        background-color: $cube-darkGreen;
        color: white;
        margin-left: 20px;
    }

    .mybtn:hover {
            background-color: $cube-mustard;
        }
</style>


