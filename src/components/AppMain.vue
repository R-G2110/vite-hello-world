<script>
	export default {
		name: 'AppMain',

	}
</script>

<template>
	<section>

      <div class="container flex">

        <div class="big-column">
          <img src="img/item1.svg" alt="item1">
        </div>

        <div class="small-column">
          <h2>Un luogo a invito con tutto lo spazio neccessario per parlare</h2>
          <p>
            I server Discord sono organizzati in canali tematici in cui puoi collaborare, condividere o semplicemente parlare della tua giornata senza intasare una chat di gruppo.
          </p>
        </div>

      </div>

    </section>
    
    <div class="wave">
    
      <img src="img/wave.svg" alt="wave">

    </div>
</template>

<style>
	.big-column {
  	width: 65%;
	}

	.small-column {
	  width: 35%;
	  margin: 25px auto;
	}
</style>