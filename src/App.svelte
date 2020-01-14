<script>
	import Tailwindcss from './Tailwindcss.svelte';
</script>

<main class="p-10">
	<h1 class="text-center uppercase">Hello {name}!</h1>
	<p class="text-center">Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
</main>

<style>
	main {
		max-width: 240px;
		@apply mx-auto;
	}

	h1 {
		color: #ff3e00;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>