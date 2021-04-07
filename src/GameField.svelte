<script>
    export let fieldContent;
</script>

<div class="field-container">
    {fieldContent}
</div>

<style>
    .field-container {
        width: 125px;
        height: 125px;
        border: 1px black solid;
        flex: 1;
        font-size: 75px;
        text-align: center;
        line-height: 125px;
        cursor: pointer;
    }
</style>