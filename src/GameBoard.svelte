<script>
    import GameField from './GameField.svelte'
</script>


<div class="board-row">
    <GameField fieldContent="X"/>
    <GameField fieldContent="X"/>
    <GameField fieldContent="X"/>
</div>

<div class="board-row">
    <GameField fieldContent="X"/>
    <GameField fieldContent="X"/>
    <GameField fieldContent="X"/>
</div>

<div class="board-row">
    <GameField fieldContent="X"/>
    <GameField fieldContent="X"/>
    <GameField fieldContent="X"/>
</div>
<button>New Game</button>
<style>
    .board-row {
        display: flex;
        flex-wrap: wrap;
    }

    button {
        width: 100%;
        margin-top: 20px;
        border-radius: 0;
        background-color: #60A5FA;
        font-size: 30px;
        cursor: pointer;
    }

    button:hover {
        outline: none;
    }
</style>