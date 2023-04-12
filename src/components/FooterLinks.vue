<script>

    import FooterCard from './FooterCard.vue';

    export default {
        name: "FooterLinks",
        components: {
            FooterCard
        }
    }
</script>

<template>
    <div class="footerTop container-fluid py-5">
        <div class="container py-5">
            <img class="imgStyle my-3 img-fluid" src="../assets/img/true-next-gen-performance.png" alt="logo azienda">
            <div class="py-3">
                <span>A Functional HTML Template for Corporate & Business.</span>
            </div>

            <div class="divider py-3">
                <i class="contacts fa-solid fa-phone"></i>
                <span>+1 (305) 1234-5678</span>
            </div>
            

            <div class="divider py-3">
                <i class="contacts fa-solid fa-envelope"></i>
                <span>hello@example.com</span>
            </div>
            
            <div class="divider py-3">
                <i class="contacts different fa-solid fa-location-dot"></i>
                <span>Main Avenue, 987</span>
            </div>

            <div class="py-4">
                <a href="#">GET IN TOUCH</a>
            </div>

            <FooterCard />
        </div>
    </div>

</template>

<style scoped lang="scss">
    @import "../styles/general.scss";

    .footerTop {
        background-color: $cut-black;
        .container {
            color: $cube-lightGray;
        }
        .imgStyle {
            filter: invert(48%) sepia(13%) saturate(3207%) hue-rotate(130deg) brightness(95%) contrast(80%);
            height: 50px;
        }

        .contacts {
            padding-right: 10px;
        }

        a {
            text-decoration: none;
            padding: 10px 20px;
            border-radius: 5px;
            color: $cube-white;
            border: solid 1px $cube-darkGreen;
            font-weight: bolder;
        }
        a:hover {
            color: $cut-black;
            background-color: $cube-mustard;
        }
    }
</style>