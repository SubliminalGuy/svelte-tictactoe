<script>
    import GameField from './GameField.svelte'
    let initialField = ["","","","","","","","",""]
</script>



<div class="board-container">
    {#each initialField as field }
    <GameField fieldContent={field}/>
    {/each}

</div>

<style>
    .board-container {
        width: 450px;
        height: 450px;
        display: flex;
        flex-wrap: wrap;
    }
</style>