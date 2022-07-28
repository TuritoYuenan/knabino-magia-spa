<script>
	import Title from "./components/Title.svelte";
	import Header from "./components/Header.svelte";
	import Footer from "./components/Footer.svelte";

	const topic = "Story"
</script>

<Title title={topic}/>
<Header {topic}/>
<main>
	<p>Read the Story</p>
</main>
<Footer/>
