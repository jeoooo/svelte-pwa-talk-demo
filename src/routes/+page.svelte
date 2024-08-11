<script>
	import ComponentWithProps from '$lib/ComponentWithProps.svelte';
	import BasicComponent from './../lib/BasicComponent.svelte';
</script>

<!-- basic component -->
<BasicComponent />

<!-- component with props (default) -->
<ComponentWithProps />

<!--  -->
<ComponentWithProps text="hello" backgroundColor="#ba2a20" textColor="white" />
