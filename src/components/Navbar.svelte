<script lang="ts">
	import NavComponent from './NavComponent.svelte';
</script>

<nav>
	<NavComponent text={'Home Page'} link={'/'} />
	<NavComponent text={'About me'} link={'about'} />
	<NavComponent text={'Projects'} link={'projects'} />
	<NavComponent text={'Contact me'} link={'contacts'} />
</nav>
