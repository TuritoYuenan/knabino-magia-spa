<script>
	import Title from "./components/Title.svelte";
	import Header from "./components/Header.svelte";
	import Footer from "./components/Footer.svelte";

	const topic = "Magical Girls";
</script>

<Title title={topic} />
<main>
	<Header {topic} />
	<p>
		Magical girls are the main type of character in the fiction. They are
		teenage girls from 13 to 20 years old who are given magical powers
	</p>
	<p>
		There are 3 ways a Magical girl can get their magical power: from Sun,
		from Moon and by an Energy Unit (most popularly a Soul gem)
	</p>
	<Footer />
</main>
