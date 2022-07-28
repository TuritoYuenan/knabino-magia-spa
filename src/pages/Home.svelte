<script>
	import Title from "./components/Title.svelte";
	import Footer from "./components/Footer.svelte";
	import Symbol from "./components/Symbol.svelte";

	const alt = "Content navigation icon";
</script>

<Title title="Homepage" />
<header>
	<Symbol height="16em" />
	<h1>Knabino Magia</h1>
</header>
<main>
	<h2>What is it?</h2>
	<p>
		Knabino Magia (Esperanto for 'magical girl') is a fictional work that
		circulates around the stories of magical girls from different nations,
		on an alternative version of planet Earth, nicknamed 'Magitero'
		(Esperanto for "magical earth")
	</p>
	<h2>Contents</h2><br />
	<section class="grid" id="contents">
		<a href="#/magical-girls"><img {alt} src="icons/magi.svg" />Magical Girls</a>
		<a href="#/fic-countries"><img {alt} src="icons/flag.svg" />Fictional Countries</a>
		<a href="#/read-thestory"><img {alt} src="icons/book.svg" />Read the Story</a>
	</section>
</main>
<Footer />

<style>
	header {text-align: center}
	#contents {display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr))}
	#contents a {padding: 1em; background: var(--dcl-bg); text-align: center}
	#contents a img {display: block; margin: auto; height: 10em}
</style>
