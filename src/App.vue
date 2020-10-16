<template>
	<div id="app">
		<!--img alt="Vue logo" src="https://vuejs.org/images/logo.png"-->
		<HelloWorld msg="Mike Kowols" greeting="Greetings Earthlings!" />

	</div>

</template>

<script>
	import HelloWorld from './components/HelloWorld.vue'

  export default {
    name: 'App',
    components: {
      HelloWorld
  }
}
</script>

<style>
	#app {
		font-family: Roboto;
		-webkit-font-smoothing: antialiased;
		-moz-osx-font-smoothing: grayscale;
		text-align: center;
		color: #1a3665;
		margin-top: 20px;
	}
</style>