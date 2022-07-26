<script>
	import Symbol from "./Symbol.svelte";

	export let topic = '';
</script>

<header>
	<Symbol height="5em" float="right"/>
	<h1><a href="#/">Knabino Magia</a></h1>
	{#if topic}	<h2>{topic}</h2> {/if}
</header>
