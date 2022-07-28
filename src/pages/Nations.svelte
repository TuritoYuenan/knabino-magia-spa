<script>
	import Title from "./components/Title.svelte";
	import Header from "./components/Header.svelte";
	import Footer from "./components/Footer.svelte";

	const topic = "Fictional Countries"
	const f = 'flags/', alt = 'Flag'
</script>

<Title title={topic} />
<Header {topic} />
<main>
	<p>
		On this alternate version of Earth, most of the countries are the same
		while there are new fictional countries replace or separate from others.
	</p>
	<section id="countries">
		<a href="BalticUni"><img {alt} src="{f}BalticUni.svg">Baltic Union</a>
		<a href="Awterosia"><img {alt} src="{f}Awterosia.svg">Awterosia</a>
		<a href="Kurdistan"><img {alt} src="{f}Kurdistan.svg">Kurdistan</a>
		<a href="MagiNihon"><img {alt} src="{f}MagiNihon.svg">Maginihon</a>
		<a href="MshrqArab"><img {alt} src="{f}MshrqArab.svg">Mashriq Arabia</a>
		<a href="NewIsrael"><img {alt} src="{f}NewIsrael.svg">New Israel</a>
	</section>
</main>
<Footer />

<style>
	#countries {
		text-align: center; display: grid;
		grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
	} #countries * {padding: .2em;}
</style>
