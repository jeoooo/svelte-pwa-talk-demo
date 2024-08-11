<script>
	// Supports weights 100-900
	import '@fontsource-variable/overpass';

	export let text = 'default text';
	export let backgroundColor = 'orange';
	export let textColor = 'black';
</script>

<div class="basic-component" style="background-color: {backgroundColor};">
	<p class="basic-component-text" style="color: {textColor};">{text}</p>
</div>

<style>
	.basic-component {
		width: fit-content;
		padding: 12px;
		border-radius: 15px;
		margin: 10px;
	}
	.basic-component-text {
		font-family: 'Overpass', sans-serif;
	}
</style>
