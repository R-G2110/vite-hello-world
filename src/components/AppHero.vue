<script>
	export default {
		name: 'AppHero',
		data(){
			return {
				title: 'Il tuo posto per parlare',
				content: ' Che tu faccia parte di un club scolastico, un gruppo di gamer, una community artistica mondiale o dove trascorrere tempo assieme a un piccolo gruppo di amici che vuole passare il tempo assieme, Discord rende piu facile chiacchierare ogni giorno e ritrovarsi più spesso.',
				src: 'img/jumbo.png'
			}
		}
	}
</script>

<template>
	<div id="jumbotron">
		<h1>{{ title }}</h1>
      <div class="content">{{ content }}</div>
      <div class="cta">
        <button class="btn big-btn">&#x2193;Scarica per Mac</button>
        <button class="btn big-btn">Apri Discord nel tuo browser</button>
      </div>
	
	</div>
</template>


<style scoped>
	#jumbotron {
		padding: 120px;
		display: flex;
		flex-direction: column;
  	justify-content: center;
  	align-items: center;
  	height: 800px;
		background-image: url(/img/jumbo.png);
		background-size: cover;
		background-position: center;
		color: white;
	}
	#jumbotron .content {
		margin: 50px 0;
		text-align: center;
		width: 780px;
		font-size: 1.3rem;
	}


</style>