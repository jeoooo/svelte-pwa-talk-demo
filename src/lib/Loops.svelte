<script>
	// Array of items
	let items = ['Apple', 'Banana', 'Orange', 'Grapes'];

	let fruits = [
		{ name: 'Apple', color: 'Red' },
		{ name: 'Banana', color: 'Yellow' },
		{ name: 'Orange', color: 'Orange' },
		{ name: 'Grapes', color: 'Purple' }
	];
</script>

<!-- Using {#each} to loop over the items array and array of objects-->
<ul>
	<h2>Using loops over the items array</h2>
	{#each items as item}
		<li>{item}</li>
	{/each}

	<h2>Using loops over the array of objects</h2>
	{#each fruits as fruit}
		<li>{fruit.name} is {fruit.color}</li>
	{/each}
</ul>
