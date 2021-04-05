<script>
	import _ from 'lodash';
	import Tree from './Tree.svelte'

	const firstTokens = _.shuffle([2,6,3,3,3,4,4,4,5,5,5]);
	const secondTokens = _.shuffle([2,2,1,1,1,1,1,1,1,1,1]);

</script>

<main class="small-container">
	<h1>Sequoia</h1>

	{#each Array(11) as _, i}
		<Tree treeNum={i + 2} firstToken={firstTokens[i]} secondToken={secondTokens[i]}/>
	{/each}

</main>

<style>

</style>