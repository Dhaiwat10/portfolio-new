<script lang="ts">
	import { page } from '$app/stores';
	import logo from './svelte-logo.svg';
</script>

<header>
	<nav class="flex gap-4 text-center mx-auto">
		<h3>Dhaiwat Pandya</h3>
		<ul class="nav-items">
			<li><a sveltekit:prefetch href="/">Home</a></li>
			<li><a sveltekit:prefetch href="/blog">Blog</a></li>
		</ul>
	</nav>
</header>
