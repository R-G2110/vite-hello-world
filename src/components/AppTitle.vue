<script>
	export default {
		name: 'AppTitle',
		data() {
			return {
				title: 'La mia prima app con Vite!'
			}
		}
	}
</script>

<template>
	<header>
		<h1>{{ title }}</h1>
	</header>
</template>


<style scoped>
	header {
		text-align: center;
 		position: fixed;
  	z-index: 999;
  	width: 100%;
  	height: 70px;
  	background-color: #FF6900;
		color: white;
	}
</style>