<script>
	import BasicRoutingDemo from '$lib/BasicRoutingDemo.svelte';
	import ButtonClickDemo from '$lib/Reactivity.svelte';
	import ComponentWithProps from '$lib/ComponentWithProps.svelte';
	import Logic from '$lib/Logic.svelte';
	import Loops from '$lib/Loops.svelte';
	import BasicComponent from './../lib/BasicComponent.svelte';
	import Reactivity from '$lib/Reactivity.svelte';
</script>

<!-- Centered container for the title -->
<div class="center-container">
	<h1>Svelte Demo</h1>
</div>

<!-- Grid container for other components -->
<div class="grid-container">
	<div class="grid-item">
		<h1>Basic Routing</h1>
		<BasicRoutingDemo />
	</div>

	<div class="grid-item">
		<h1>Basic Component</h1>
		<BasicComponent />
	</div>

	<div class="grid-item">
		<h1>Component with Props (Default)</h1>
		<ComponentWithProps />
	</div>

	<div class="grid-item">
		<h1>Component with Props</h1>
		<ComponentWithProps text="hello" backgroundColor="#ba2a20" textColor="white" />
	</div>

	<div class="grid-item">
		<h1>Reactivity</h1>
		<Reactivity />
	</div>

	<div class="grid-item">
		<h1>Logic</h1>
		<Logic x={5} />
	</div>

	<div class="grid-item">
		<h1>Loops</h1>
		<Loops />
	</div>

	<div class="grid-item">
		<h1>For more on Svelte stuff <a href="https://svelte.dev/examples/hello-world">go here</a></h1>
	</div>
</div>

<style>
	/* Center container for the title */
	.center-container {
		text-align: center; /* Center the text horizontally */
		margin: 20px; /* Add some margin for spacing */
	}

	/* Grid container styling */
	.grid-container {
		display: grid;
		grid-template-columns: repeat(2, 1fr); /* 2 columns, each taking equal space */
		gap: 16px; /* Adjust spacing between grid items */
		padding: 16px;
	}

	/* Grid item styling */
	.grid-item {
		background-color: #f9f9f9; /* Background color for grid items */
		border: 1px solid #ddd; /* Border for grid items */
		border-radius: 8px; /* Rounded corners */
		padding: 16px; /* Padding inside grid items */
		box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Shadow effect */
	}
</style>
