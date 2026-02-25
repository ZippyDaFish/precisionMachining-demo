<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>

<header class="absolute top-0 left-0 w-full p-8">
	<div class="flex items-center cursor-pointer justify-center w-16 h-16 border-2 border-[var(--color-primary)] rounded-[var(--radius-md)]">
		<h1 class="text-xs">JB Tool</h1>
	</div>
</header>
{@render children()}
<footer></footer>