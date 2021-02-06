<script lang="ts">
	import Nav from '../components/Nav.svelte';
	import Tailwindcss from '../components/Tailwind.svelte';
	export let segment: string;
</script>

<style global>
	@tailwind base;
    @tailwind components;
    @tailwind utilities;
</style>

<Tailwindcss />

<Nav {segment}/>

<main>
	<slot></slot>
</main>