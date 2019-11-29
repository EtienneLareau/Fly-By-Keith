<script>
	export let name;
	let temp = 'good';
	let cloud = 'Some'
</script>

<main>
	<h1>Fly By Keith</h1>
	<p>Welcome {name}</p>

	<p>Would you like to fly with us today ? Temperature is {temp}. {cloud} clouds are around and there's no wind.</p>
	<p>Would you like to fly today?</p>

	<label for="yes">
		<input type="checkbox" id="yes" />
		Yes
	</label>
</main>

<style>
	input [type=checkbox] {
		width: 40px;
	}
	

	main {
		text-align: center;
		padding: 1em;
		max-width: 840px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 900;
		font-style: italic;
	}

	p {
		font-size: 2em;
	}

	@media (max-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>