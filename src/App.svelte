<script>
import Header from "./components/Header.svelte";
import Footer from "./components/Footer.svelte";

const btn = "Content Navigation Icon"
</script>

<Header/>
<main>
	<h2>What is it?</h2>
	<p>
		Knabino Magia (Esperanto for 'magical girl') is a fictional work
		that circulates around the stories of magical girls from different
		nations, on an alternative version of planet Earth, nicknamed
		'Magitero' (Esperanto for "magical earth")
	</p>
	<h2>Contents</h2><br/>
	<section class="contents">
		<a href="./#"><img src="/svg/magi.svg" alt="{btn}">Magical Girls</a>
		<a href="./#"><img src="/svg/flag.svg" alt="{btn}">Fictional Countries</a>
		<a href="./#"><img src="/svg/book.svg" alt="{btn}">Read the Story</a>
	</section>
</main>
<Footer/>

<style>
	.contents {display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));}
	.contents a img {margin: auto; height: 10em; display: block;}
	.contents a {
		padding: 1em; background: var(--dcl-bg);
		text-align: center;
	}
</style>
