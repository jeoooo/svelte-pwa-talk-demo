<script>
	let count = 0;

	function handleClick() {
		count += 1;
	}
</script>

<button on:click={handleClick}>
	Clicked {count}
	{count === 1 ? 'time' : 'times'}
</button>

<style>
	button {
		background-color: orange;
		color: black;
		border: none;
		border-radius: 8px;
		padding: 12px;
		cursor: pointer;
		font-size: 16px;
		margin: 10px;
	}

	button:hover {
		background-color: darkorange;
	}
</style>
