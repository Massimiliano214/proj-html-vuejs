<script>
    export default {
        name: "FooterCard",
        data() {
            return {
                aboutList: ["The Company", "Institutional", "Social & Events", "Innovation", "Environment", "technology"],
                transportList: ["Industrialized", "Chemicals", "Packaged Liquids", "Construction", "Laminated Wood", "And others"],
                supportList: ["Responsibility", "Terms of Use", "About Cookies", "Privacy Policy", "Accessibility", "information"]
            }
        }
    }
</script>

<template>
    <div class="myCard py-5 px-5">
        <h4 class="py-3">About</h4>
        <ul v-for="(item, index) in aboutList" :key="index">
            <li>
                <i class="myStyle fa-solid fa-chevron-right"></i>
                <a href="#"> {{ item }}</a>
            </li>
            
        </ul>
    </div>

    <div class="myCard py-5 px-5">
        <h4 class="py-3">Transport</h4>
        <ul v-for="(item, index) in transportList" :key="index">
            <li>
                <i class="myStyle fa-solid fa-chevron-right"></i>
                <a href="#"> {{ item }}</a>
            </li>
            
        </ul>
    </div>

    <div class="myCard py-5 px-5">
        <h4 class="py-3">Support</h4>
        <ul v-for="(item, index) in supportList" :key="index">
            <li>
               <i class="myStyle fa-solid fa-chevron-right"></i>
                <a href="#"> {{ item }}</a> 
            </li>
            
        </ul>
    </div>

</template>


<style scoped lang="scss">
    @import "../styles/general.scss";

    .myCard {
        width: 22%;
        background-color: rgba($cube-white, $alpha: 0.1);
        border-radius: 5px;

        a {
            text-decoration: none;
            color: $cube-lightGray;
        }

        .myStyle {
            padding-right: 10px;
        }

        li {
            list-style-type: none;
        }

        ul {
            padding-left: 0;
        }
        h4 {
            color: $cube-white;
        }
    }
</style>