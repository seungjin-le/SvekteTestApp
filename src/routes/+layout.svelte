<script>
		import '../lib/styless/tailwindcss.css';
	import Header from './Header.svelte';
	import Footer from './Footer.svelte';
	import Container from './Container.svelte';
</script>

<div class="bg-[gray] w-full h-full min-h-screen	">
	<div class="text-column text-white text-[32px] font-bold">
		<h1>Main Layout</h1>      
	</div>
	<Header />
	<Container>
		<slot />
	</Container>
	<Footer />
</div>

