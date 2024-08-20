<script>
	import BasicRoutingDemo from '$lib/BasicRoutingDemo.svelte';
	import ButtonClickDemo from '$lib/ButtonClickDemo.svelte';
	import ComponentWithProps from '$lib/ComponentWithProps.svelte';
	import Logic from '$lib/Logic.svelte';
	import BasicComponent from './../lib/BasicComponent.svelte';
</script>

<!-- basic component -->

<h1>Svelte Demo</h1>

<h1>Basic Routing</h1>
<BasicRoutingDemo />

<h1>Basic Component</h1>
<BasicComponent />

<!-- component with props (default) -->
<h1>component with props (default)</h1>
<ComponentWithProps />

<!-- component with props -->

<h1>component with props</h1>
<ComponentWithProps text="hello" backgroundColor="#ba2a20" textColor="white" />

<!-- reactivity -->
<h1>Reactivity</h1>
<ButtonClickDemo />

<h1>Logic</h1>
<Logic x={5} />

<h1>
	for more on Svelte stuff <a href="https://svelte.dev/examples/hello-world">go here</a>
</h1>
