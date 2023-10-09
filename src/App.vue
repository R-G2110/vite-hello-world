<script>
  import AppTitle from './components/AppTitle.vue';
  import Jumbotron from './components/Jumbotron.vue';
  import Footer from './components/Footer.vue';
  export default {
    name: 'App',
    components: {
      AppTitle,
      Jumbotron,
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
  <Jumbotron />
  <Footer />
</template>



<style>
  
</style>