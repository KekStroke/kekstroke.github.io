<script lang="ts" context="module">
	import Navbar from '../components/Navbar.svelte';
	import Footer from '../components/Footer.svelte';
</script>

<svelte:head>
	<link rel="stylesheet" href="global.css" />
	<link
		href="https://fonts.googleapis.com/css2?family=Work+Sans:wght@400;700&display=swap"
		rel="stylesheet"
	/>
</svelte:head>

<Navbar />

<slot />

<Footer />
