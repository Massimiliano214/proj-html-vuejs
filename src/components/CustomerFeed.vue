<script>
    import CardFeedback from './CardFeedback.vue';

    export default {
        name: "CustomFeed",
        components: {
            CardFeedback
        }
    }
</script>


<template>
    <div class="feedShell container-fluid py-5">
        <div class="container text-center py-5">
            <h6>CUSTOMER TESTIMONIALS</h6>
            <h2 class="py-4">Trusted <mark>Feedback</mark></h2>

            <p>We work intensively in search of ideals that can add up in the lives of out customers. This is what moves us and we are grateful for the recognition.</p>

            <CardFeedback />
        </div>  
    </div>
    
</template>


<style scoped lang="scss">
    @import "../styles/general.scss";

    .feedShell {
        background-color: $cut-black;

        h6 {
            color: $cube-lightGreen;
        }

        h2 {
            color: $cube-white;
            font-weight: bolder;
            font-size: 3rem;

            mark {
                color: $cube-white;
                background-color: rgba($cube-lightGreen, $alpha: 0.2);
            }
        }

        p {
            color: $cube-lightGray;
        }
    }
</style>