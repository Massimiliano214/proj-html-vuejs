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
                <div class="container">
                <div class="imageCompany">
                    <img src="../assets/img/true-next-gen-performance.png" alt="">

                </div>

                <nav class="links">
                    <ul>
                        <li v-for="(link, index) in navList" :key="index"> {{ link }}</li>
                    </ul>
                </nav>
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
    }

    
</style>