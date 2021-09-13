<script context="module" lang="ts">
	export const prerender = true;
</script>

<svelte:head>
	<title>Home</title>
</svelte:head>

<main>
	<img class="rounded-full h-48 mx-auto" src="/avi.jpeg" alt="Dhaiwat" />

	<div class="flex flex-col gap-6 mx-auto items-left my-6 text-left">
		<p>> Hi!👋 I'm Dhaiwat. I am a 20-year-old software engineer.</p>

		<p>> ⚡️ I am highly proficient with React, TypeScript and Serverless.</p>

		<p>> ✍ I write about building quality software at my blog and speak at conferences.</p>

		<p>
			> 💻 My best work: <a href="https://github.com/dhaiwat10/react-link-preview" target="_blank"
				>react-link-preview</a
			>,
			<a href="https://github.com/dhaiwat10/react-agora" target="_blank">react-agora</a>,
			<a
				href="https://blog.dhaiwatpandya.com/develop-and-test-react-components-in-isolation"
				target="_blank">Develop & test React components in isolation</a
			>
		</p>

		<p>
			> ❤️ Open-source projects I've contributed to: <a
				href="https://github.com/supabase/supabase"
				target="_blank">Supabase</a
			>, <a href="https://github.com/developer-dao" target="_blank">Developer DAO</a>,
			<a href="https://github.com/dailydotdev/apps" target="_blank">daily.dev</a>
		</p>
	</div>
</main>

<style>
	a {
		/* color: #00b2e2; */
		text-decoration: underline;
		text-decoration-color: rgb(48, 180, 103);
	}
</style>
