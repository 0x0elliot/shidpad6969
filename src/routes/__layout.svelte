<script lang="ts">
	import Footer from '$lib/components/FooterComponent.svelte';
	import Header from '$lib/components/HeaderComponent.svelte';
	import { MetaTags } from 'svelte-meta-tags';
	import '../app.css';
</script>

<MetaTags
	title="ShidPad69"
	description="shid"
/>

<svelte:head>
	<title>ShidPad69</title>
</svelte:head>

<div class="flex flex-col min-h-screen bg-white max-w-5xl mx-auto">
	<Header />
	<main class="flex-1">
		<div class="mx-auto">
			<slot />
		</div>
	</main>
	<Footer />
</div>
