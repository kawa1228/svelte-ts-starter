<Header/>
<main>
	<Router {routes}/>
</main>

<script lang="typescript">
	import Header from "./components/Header.svelte";

	import Router from 'svelte-spa-router'
	import routes from './routes'
</script>

<style lang="scss">
	main {
		text-align: center;
		max-width: 240px;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
