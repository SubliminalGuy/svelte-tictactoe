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
	

	.container {
		width: 475px;
		height: 1000px;
		margin: 0 auto;
		
	}

</style>