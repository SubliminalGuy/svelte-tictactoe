<script>
	import Title from './Title.svelte';
	import GameData from './GameData.svelte';
	import GameBoard from './GameBoard.svelte';
</script>

<main>
	<div class="container">
		<Title />
		<GameData />
		<GameBoard />
	</div>
	
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	.container {
		width: 50%;
		margin: 0 auto;
		display: flex;
		flex-wrap: wrap;
		justify-content: center;
	}

	h1 {
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