<h1>Hello {name}!</h1>
<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>

<h2 class="routetitle">Home!</h2>

<p>Welcome to this sample code!</p>

<script lang="typescript">
	export let name: string = 'world';
</script>


<style lang="scss">
	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}
	p {
		// テスト用
		margin-bottom: 1000px;
	}
</style>
