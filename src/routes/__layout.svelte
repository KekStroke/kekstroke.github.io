<script lang="ts" context="module">
	//
	export const prerender = true;
	import Navbar from '../components/Navbar.svelte';
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
