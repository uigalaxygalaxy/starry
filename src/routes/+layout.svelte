<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';
	export const prerender = true;
	export const ssr = false;
	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
	<title>45434Y Starry</title>
</svelte:head>
{@render children()}