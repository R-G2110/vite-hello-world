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
  body {
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    font-size: 1.1rem;
  }

  h1 {
    font-size: 2.5rem;
    color: white;
  }

  h2 {
    font-size: 2.3rem;
    margin-bottom: 20px;
  }

  img {
		width: 100%;
	}

  .btn {
    margin: 0 10px;
    padding: 15px 20px;
    border: none;
    background-color: #0061FF;
    color: white;
    font-size: 1.2rem;
    border-radius: 30px;
    cursor: pointer;
  }

  .container {
    margin: 0 auto;
    width: 75%;
    max-width: 1200px;
    min-width: 900px;
  }
</style>