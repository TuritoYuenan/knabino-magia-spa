<script>
import Navbar from "./Navbar.svelte";

</script>
<Navbar/>
<main>
	<h1>What is it?</h1>
	<p>
		Knabino Magia (Esperanto for 'magical girl') is a fictional work
		that circulates around the stories of magical girls from different
		nations, on an alternative version of planet Earth, nicknamed
		'Magitero' (Esperanto for "magical earth")
	</p>
	<h1>Contents</h1><br/>
	<section class="contents">
		<a href="./#"><img src="/src/assets/magi.svg" alt="cnt">Magical Girls</a>
		<a href="./#"><img src="/src/assets/flag.svg" alt="cnt">Fictional Countries</a>
		<a href="./#"><img src="/src/assets/book.svg" alt="cnt">Read the Story</a>
	</section>
</main>

<style>
	main {padding: 1em;}
	.contents {display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));}
	.contents a img {margin: auto; height: 10em; display: block;}
	.contents a {
		padding: 1em; background: var(--dcl-bg);
		text-align: center; text-decoration: none; color: inherit;
	}
</style>
