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

      }

    }
  }
</script>

<template>
  <TheHeader />
  <MyJumbotron />
</template>

<style lang="scss">
 @use "./styles/general.scss"
</style>
