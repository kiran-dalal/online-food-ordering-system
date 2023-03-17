<script>
	const name = "kiran dalal"
	const adore = "great"
</script>


<main>
	<h2> hello {name}</h2>
	<h3>you are {adore} <br> keep it up</h3>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}
	h2{
		color: blueviolet;
	}

	h3 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>