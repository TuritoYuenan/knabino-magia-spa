<script>
	import Header from "./components/Header.svelte";
	import Footer from "./components/Footer.svelte";

	const topic = "Fictional Countries"
	const f = 'flags/'
</script>

<svelte:head>
	<title>{topic} | Knabino Magia</title>
</svelte:head>

<Header {topic} />
<main>
	<p>
		On this alternate version of Earth, most of the countries are the same
		while there are new fictional countries replace or separate from others.
	</p>
	<section id="countries">
		<a href="#/"><img alt="Flag" src="{f}BalticUni.svg">Baltic Union</a>
		<a href="#/"><img alt="Flag" src="{f}Awroteros.svg">Awroteros</a>
		<a href="#/"><img alt="Flag" src="{f}Kurdistan.svg">Kurdistan</a>
		<a href="#/"><img alt="Flag" src="{f}MagiNihon.svg">Magi Nihon</a>
		<a href="#/"><img alt="Flag" src="{f}MshrqArab.svg">Mashriq Arabia</a>
		<a href="#/"><img alt="Flag" src="{f}NewIsrael.svg">New Israel</a>
	</section>
</main>
<Footer />

<style>
	#countries {
		text-align: center; display: grid;
		grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
	} #countries * {padding: .2em;}
</style>
