<script>

  import TheHeader from "./components/TheHeader.vue";
  import MyJumbotron from "./components/MyJumbotron.vue";
  import MyDescription from "./components/MyDescription.vue";
  import ServicesDesc from "./components/ServicesDesc.vue";
  import LogisticProcedures from "./components/LogisticProcedures.vue";
  import StatsCompany from "./components/StatsCompany.vue";
  import CustomerFeed from "./components/CustomerFeed.vue";
  import FormsSector from "./components/FormsSector.vue";
  import FooterLinks from "./components/FooterLinks.vue";
  import FooterBottom from "./components/FooterBottom.vue";

  export default {
    components: {
      TheHeader,
      MyJumbotron,
      MyDescription,
      ServicesDesc,
      LogisticProcedures,
      StatsCompany,
      CustomerFeed,
      FormsSector,
      FooterLinks,
      FooterBottom
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
    
    <section id="mainServices">
      <ServicesDesc />
    </section>

    <section id="LogicProceds">
      <LogisticProcedures />
    </section>

    <section id="StatsCompany">
      <StatsCompany />
    </section>

    <section id="myFeedback">
      <CustomerFeed />
    </section>

    <section id="contactUs">
      <FormsSector />
    </section>

    <footer>
      <FooterLinks />

      <FooterBottom />
    </footer>
  </main>
  
</template>

<style lang="scss">
 @use "./styles/general.scss"
</style>
