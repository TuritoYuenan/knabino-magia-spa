<script>
	import Title from "./components/Title.svelte";
	import Header from "./components/Header.svelte";
	import Footer from "./components/Footer.svelte";

	const topic = "Countries"
	const alt = "Flag"
</script>

<Title title={topic} />
<main>
	<Header {topic} />
	<p>Countries that either don’t exist in real life (IRL) or differ in some way</p>
	<section id="countries">
		<a href="lle"><img {alt} src="flags/lle.svg">Baltic Union</a>
		<a href="nz"><img {alt} src="flags/nz.svg">Awteros</a>
		<a href="kd"><img {alt} src="flags/kd.svg">Kurdistan</a>
		<a href="jp"><img {alt} src="flags/jp.svg">Magical Japan</a>
		<a href="mq"><img {alt} src="flags/mq.svg">Mashriq Arabia</a>
		<a href="il"><img {alt} src="flags/il.svg">New Israel</a>
	</section>
	<Footer />
</main>

<style>
	#countries * {padding: .2em;}
	#countries {
		display: grid;
		grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
		text-align: center;
	}
</style>
