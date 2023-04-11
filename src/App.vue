<script>

  import TheHeader from "./components/TheHeader.vue";
  import MyJumbotron from "./components/MyJumbotron.vue";

  export default {
    components: {
      TheHeader,
      MyJumbotron,
    },
    data() {
      return {
        navList: ["HOME", "ABOUT", "SERVICES", "PROCESS", "TESTIMONIALS"],

      }

    }
  }
</script>

<template>
  <TheHeader />
  <MyJumbotron :navList="navList"/>
</template>

<style lang="scss">
 @use "./styles/general.scss"
</style>
