<script lang="ts">
	import { base } from '$app/paths';
	export let text: string;
	export let link: string;
</script>

<a class="nav-link" href="{base}/{link}">{text}</a>
<!-- <Link class="nav-link" to={link}>{text}</Link> -->
