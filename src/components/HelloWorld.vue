<template>
	<div class="hello">
		<h1 class="test">{{ msg }}</h1>

		<p>
			<a href="https://vitejs.dev" target="_blank">Vite Documentation</a>
			|
			<a href="https://vuejs.org/v2/guide/" target="_blank">
				Vue 2 Documentation
			</a>
		</p>

		<button @click="count++">count is: {{ count }}</button>
		<p>
			Edit
			<code>components/HelloWorld.vue</code> to test hot module replacement.
		</p>
	</div>
</template>

<script>
export default {
	name: 'HelloWorld',
	props: {
		msg: String,
	},
	data() {
		return {
			count: 0,
		}
	},
}
</script>

<style scoped>
a {
	color: #42b983;
}

label {
	margin: 0 0.5em;
	font-weight: bold;
}

code {
	background-color: #eee;
	padding: 2px 4px;
	border-radius: 4px;
	color: #304455;
}
</style>
