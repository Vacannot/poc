<template>
	<img alt="Vue logo" src="./assets/logo.png" />
	<ProofOf msg="Thank you it feels great to be here" />
</template>

<script>
import ProofOf from "./components/ProofOf.vue";

export default {
	name: "App",
	components: {
		ProofOf,
	},
};
</script>

<style>
#app {
	font-family: Avenir, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
	margin-top: 60px;
}
</style>
