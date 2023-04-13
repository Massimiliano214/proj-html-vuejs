<script>
    export default {
        name: "LogisticProcedures",

        data() {
            return {
                titlesList: ["Collection of information", "service Invoice Sending", "Withdrawal of Cargo", "Transport Customer Order", "Successful Delivery"]
            }
        }
    }
</script>

<template>

    <div class="container py-5 text-center">
        <h6>HOW IT WORKS IN PRACTICE</h6>
        <h2 class="py-4"><mark>Logistical</mark> Procedure</h2>

        <p>We work with innovative methodologies to ensure that the entire delivery process is done from start to finish as planned.</p>

    </div>

    <div class="container-fluid d-flex justify-content-between px-5 py-3 position-relative">
        <div class="progressLine">

        </div>

        <div v-for="(title, index) in titlesList" :key="index" class="progressiveItem px-5 text-center">
            <h3>{{ '0' + (index + 1) }}</h3>
            <h4>{{ title }}</h4>
            <p>Lorem ipsum dolor sit amet consectetur.</p>
        </div>

    </div>
</template>

<style scoped lang="scss">
    @import "../styles/general.scss";
    h3 {
        color: $cube-darkGreen;
        background-color: rgb(217, 236, 237);
        border: 1px solid $design-lightGreen;
        display: inline-block;
        padding: 10px 12px;
        border-radius: 50%;
        position: relative;
        z-index: 99999;
        
    }

    .progressLine {
        width: 100%;
        height: 10px;
        background-color: rgba($cube-darkGreen, $alpha: 0.1);
        position: absolute;
        left: 0;
        top: 39px;
        z-index: 99;
    }

    h6 {
        color: $cube-darkGreen;
    }

    h2 {
        font-size: 3rem;
        padding: 15px;
        font-weight: bolder;

        mark {
            color :$cube-darkGreen;
            background-color: rgba($cube-darkGreen, $alpha: 0.1);
        }
    }

    p {
        color: $cube-darkGray;
    }
</style>