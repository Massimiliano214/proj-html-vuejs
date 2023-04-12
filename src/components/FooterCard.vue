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
    <div class="myCard">
        <h4>About</h4>
        <div v-for="(item, index) in aboutList" :key="index">
            <i class="fa-solid fa-chevron-right"></i>
            <a href="#"> {{ item }}</a>
        </div>
    </div>

    <div class="myCard">
        <h4>Transport</h4>
        <div v-for="(item, index) in transportList" :key="index">
            <i class="fa-solid fa-chevron-right"></i>
            <a href="#"> {{ item }}</a>
        </div>
    </div>

    <div class="myCard">
        <h4>Support</h4>
        <div v-for="(item, index) in supportList" :key="index">
            <i class="fa-solid fa-chevron-right"></i>
            <a href="#"> {{ item }}</a>
        </div>
    </div>

</template>


<style scoped lang="scss">
    @import "../styles/general.scss";
</style>