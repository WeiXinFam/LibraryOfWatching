<script>
	export let name;
</script>

<main>
	<h1>Hello {name}!</h1>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
</main>

<img src="https://i.pinimg.com/564x/be/1d/6c/be1d6cfc5cfd04dad9e3faa0bad5b6e4.jpg" alt="john wick"/>
<img src="https://i.pinimg.com/564x/be/1d/6c/be1d6cfc5cfd04dad9e3faa0bad5b6e4.jpg" alt="john wick2"/>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	img{
		border-radius: 8px;
		width:8em;
		height: 15em;
		margin-left: 15em;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>