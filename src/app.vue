<template>
	<div id="app">
		<hello></hello>
	</div>
</template>

<script>
	import Hello from './components/hello/hello.vue'

	export default {
		components: {
			Hello
		}
	}
</script>

<style lang="scss">
	@import "./app.scss";
</style>
