<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>

<header class="absolute top-0 left-0 w-full p-8">
	<div class="group relative flex items-center justify-center w-16 h-16 cursor-pointer text-center">
		<!-- Rotating Border -->
		<div class="absolute inset-0 border-2 border-[var(--color-primary)] rounded-[var(--radius-md)]
					transition-transform duration-300 ease-out
					group-hover:rotate-45">
		</div>

		<!-- Accent Border -->
		<div class="absolute inset-0 bg-[var(--color-accent)] rounded-[var(--radius-md)]
					scale-0 opacity-0
					transition-all duration-300 ease-out
					group-hover:scale-150 group-hover:opacity-50">
		</div>

		<h1 class="relative text-xs font-semibold text-[var(--color-primary)]
				transition-colors duration-300 group-hover:text-[var(--color-primary)]">
			Nifty Tool LLC
		</h1>
	</div>
</header>
{@render children()}
<footer></footer>