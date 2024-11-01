
<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>


<script>
	import { onMount } from 'svelte';

	onMount(() => {
		console.log('Page mounted');
	});
	console.log('Page mounted');
</script>


<div class="bg-[red">
	Main Page
</div>