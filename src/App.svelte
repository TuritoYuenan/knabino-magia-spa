<script>
	import Router from "svelte-spa-router";

	import Home from "./pages/Home.svelte";
	import Error from "./pages/Error.svelte";
	import Knabino from "./pages/Knabino.svelte";
	import Nations from "./pages/Nations.svelte";
	import Stories from "./pages/Stories.svelte";
</script>

<Router routes={{
	"/magical-girls": Knabino,
	"/fic-countries": Nations,
	"/read-thestory": Stories,
	"/": Home, "*": Error,
}} />
