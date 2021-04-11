<script>
    export let treeNum;
    export let firstToken;
    export let secondToken;
</script>

<div on:click>
    <h1 class="text-center">Tree {treeNum}</h1>
    <h3>First: {firstToken}</h3>
    <h3>Second: {secondToken}</h3>
</div>

<style>
    div {
        border: 3px solid black;
        margin: 10px;
    }
</style>

