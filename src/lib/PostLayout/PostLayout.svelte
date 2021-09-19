<script>
	import './post-layout.css';

	export let title;
</script>

<div class='flex flex-col gap-6'>
<h1>{title}</h1>
<slot>
	<!-- the mdsvex content will be slotted in here -->
</slot>
</div>

<style>
	h1 {
		font-size: 1.5em;
    font-weight: bold;
	}
</style>
