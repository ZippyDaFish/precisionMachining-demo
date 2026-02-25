<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>

<header class="absolute top-0 left-0 w-full p-8">
	<div class="w-16 h-16 border-2 border-gray-400 rounded-full"></div>
</header>
{@render children()}
<footer></footer>