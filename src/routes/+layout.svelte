<script>
	import '$lib/styles/index.css';
</script>

<main>
	<slot />
</main>

<style>
	main {
		display: grid;
		min-height: 100vh;
		place-items: center;
	}
</style>
