<script lang="ts">
	import Header from '$lib/header/Header.svelte';
	import '../app.css';

	const description =
		'I am Dhaiwat - a 20-year-old software engineer skilled with React, TypeScript, Web3 and more!';
</script>

<svelte:head>
	<meta property="og:image" content="/thumb.png" />
	<meta name="description" content={description} />

	<!-- Twitter -->
	<meta name="twitter:card" content="summary_large_image" />
	<meta name="twitter:site" content="@dhaiwat10" />
	<meta name="twitter:creator" content="@dhaiwat10" />
	<meta name="twitter:title" content="Dhaiwat Pandya - Software Engineer" />
	<meta name="twitter:description" content={description} />
	<meta name="twitter:image" content='/thumb.png' />

	<title>Dhaiwat Pandya</title>
	<link rel="icon" href='/favicon.png' />
</svelte:head>

<!-- <Header /> -->

<main>
	<slot />
</main>

<!-- <footer>
	<p>visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to learn SvelteKit</p>
</footer> -->

<style>
	@tailwind base;
	@tailwind components;
	@tailwind utilities;
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
</style>
