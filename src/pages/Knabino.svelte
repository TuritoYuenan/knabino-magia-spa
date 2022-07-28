<script>
	import Title from "./components/Title.svelte";
	import Header from "./components/Header.svelte";
	import Footer from "./components/Footer.svelte";

	const topic = "Magical Girls"
</script>

<Title title={topic} />
<Header {topic} />
<main>
	<p>Magical girls are the main characters and
	central focus of this fiction</p>
</main>
<Footer />
