<script>

  import TheHeader from "./components/TheHeader.vue";
  import MyJumbotron from "./components/MyJumbotron.vue";
  import MyDescription from "./components/MyDescription.vue";

  export default {
    components: {
      TheHeader,
      MyJumbotron,
      MyDescription,
    },
    data() {
      return {
        navList: ["HOME", "ABOUT", "SERVICES", "PROCESS", "TESTIMONIALS"],

      }

    }
  }
</script>

<template>
  <header>
    <TheHeader />
  </header>
  <main>
    <section id="jumbotron">
      <MyJumbotron :navList="navList"/>
    </section>
    
    <section id="siteDescription">
      <MyDescription></MyDescription>
    </section>
    
  </main>
  
</template>

<style lang="scss">
 @use "./styles/general.scss"
</style>
