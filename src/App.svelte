<script>
	export let name;
</script>

<main>
	<h1 class='text-center'>Hello {name}!</h1>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
</main>

<style global>
	@tailwind base;
	@tailwind components;
	@tailwind utilities;
</style>