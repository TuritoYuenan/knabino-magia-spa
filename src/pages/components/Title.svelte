<script>
	export let title = ""
</script>

<svelte:head>
	<title>{title} | Knabino Magia</title>
</svelte:head>
<nav>
	<strong><a href="/">Knabino Magia</a></strong>
	<section class="nav__right">
		<a href="#/magical-girls">Magical Girls</a>
		<a href="#/fic-countries">Countries</a>
		<a href="#/read-thestory"><b>Story</b></a>
	</section>
</nav>

<style>
	nav {padding: 1rem;background: var(--dcl-bg);}
	.nav__right {float: right;}
	.nav__right * {margin: auto .5rem; font-size: large;}
</style>
