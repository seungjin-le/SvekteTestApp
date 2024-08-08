<script>
		import '../lib/styless/tailwindcss.css';
	import Header from './Header.svelte';
	import Footer from './Footer.svelte';
	import Container from './Container.svelte';
</script>

<div class="app">
	<Header />
	<Container>
		<slot />
	</Container>
	<Footer />
</div>

