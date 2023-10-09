<script>
	export default {
		name: 'AppHero',
		data(){
			return {
				p: 'Questo è la parte di Jumbotron',
				src: 'img/jumbo.png'
			}
		}
	}
</script>

<template>
	<h1>{{ p }}</h1>
	<div id="jumbotron">
		<img :src="src" alt="jumbo">
	</div>
</template>


<style scoped>
	img {
		width: 100%;
	}
	#jumbotron {
  	justify-content: center;
  	align-items: center;
  	height: 730px;
	}
</style>