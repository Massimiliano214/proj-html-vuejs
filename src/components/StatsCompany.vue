<script>
    export default {
        name: "StatsCompany"
    }
</script>

<template>
    <div class="myJumbo container-fluid py-5 d-flex align-items-center">
        <div class="container text-center">
            <h6>WHAT ARE WE DOING</h6>
            <h2 class="py-4"><mark>Results</mark> in Numbers</h2>

            <div class="statSection d-flex justify-content-between py-5">
                <div class="stat">
                    <h3>128</h3>
                    <h4>Certifications</h4>
                </div>

                <div class="stat">
                    <h3>230</h3>
                    <h4>Employees</h4>
                </div>

                <div class="stat">
                    <h3>517</h3>
                    <h4>Customers</h4>
                </div>

                <div class="stat">
                    <h3>94</h3>
                    <h4>Countries Served</h4>
                </div>
            </div>
            
        </div>
    </div>
    
</template>

<style scoped lang="scss">
    @import "../styles/general.scss";

    .myJumbo {
        background-image: url("../assets/img/bg-10.jpg");
        background-position: center;
        margin-top: 50px;
        height: 550px;

        h6 {
            color: $cube-lightGreen;
        }

        h2 {
            font-size: 3rem;
            color: $cube-white;
            font-weight: bolder;

            mark {
                background-color: rgba($cube-lightGreen, $alpha: 0.2);
                color: $cube-white;
            }
        }
        .statSection {
            h3 {
                color: $cube-lightGreen;
            }
            h4 {
                color: $cube-white;
            }
        }
    }
</style>