<script>
	import Tree from './Tree.svelte'

	const firstTokens = [2,6,3,3,3,4,4,4,5,5,5];
	const secondTokens =[2,2,1,1,1,1,1,1,1,1,1];
</script>

<main class="small-container">
	<h1>Sequoia</h1>
	<Tree treeNum={2} firstToken={2} secondToken={2} />
	<Tree treeNum={3} firstToken={6} secondToken={2} />
	<Tree treeNum={4} firstToken={3} secondToken={1} />
	<Tree treeNum={5} firstToken={3} secondToken={1} />
	<Tree treeNum={6} firstToken={3} secondToken={1} />
	<Tree treeNum={7} firstToken={4} secondToken={1} />
	<Tree treeNum={8} firstToken={4} secondToken={1} />
	<Tree treeNum={9} firstToken={4} secondToken={1} />
	<Tree treeNum={10} firstToken={5} secondToken={1} />
	<Tree treeNum={11} firstToken={5} secondToken={1} />
	<Tree treeNum={12} firstToken={5} secondToken={1} />
</main>

<style>

</style>