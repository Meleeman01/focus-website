<script>
	import Header from '$lib/header/Header.svelte';
	import '../app.css';
</script>

<h1>FoCUS (UK)</h1>
<h3>Future of coding mini conference and retreat</h3>
<Header />

<main>
	<slot />
</main>

<footer>
	<p>Created with ❤ by Meleeman</p>
</footer>

<style>
	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		padding: 1rem;
		width: 100%;
		max-width: 1024px;
		margin: 0 auto;
		box-sizing: border-box;
	}
	h1 {
		font-size: 3rem;
	}
	h3 {
		color: var(--heading-color);
		font-weight: 400;
		text-align: center;
	}

	footer {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		padding: 40px;
	}


	@media (min-width: 480px) {
		footer {
			padding: 40px 0;
		}
	}
</style>
