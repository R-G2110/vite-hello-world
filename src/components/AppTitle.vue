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
		padding: 20px 0;
		text-align: center;
 		position: fixed;
  	z-index: 999;
  	width: 100%;
  	height: 70px;
  	background-color: #2A5EE8;
		color: white;
	}
</style>