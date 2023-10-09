<script>
  import AppTitle from './components/AppTitle.vue';
  import AppHero from './components/AppHero.vue';
  import Footer from './components/Footer.vue';
  export default {
    name: 'App',
    components: {
      AppTitle,
      AppHero,
      Footer
    },
    data(){
      return {
        
      }
    }
}
</script>

<template>
  <AppTitle />
  <AppHero />
  <Footer />
</template>



<style>
  
</style>