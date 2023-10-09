<script>
  import Header from './components/Header.vue';
  import Jumbotron from './components/Jumbotron.vue';
  import Footer from './components/Footer.vue';
  export default {
    name: 'App',
    components: {
      Header,
      Jumbotron,
      Footer
    },
    data(){
      return {
        title: 'HELLO MOTO'
      }
    }
}
</script>

<template>
  <Header />
  <Jumbotron />
  <h1>{{ title }}</h1>
  <Footer />
</template>



<style>

</style>