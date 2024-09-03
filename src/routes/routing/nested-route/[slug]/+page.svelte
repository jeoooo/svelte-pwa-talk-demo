<script lang="ts">
	import { page } from '$app/stores';

	// Access the dynamic slug from the URL
	const slug = $page.params.slug;
</script>

<h1>Nested Route with Slug</h1>
<p>You are viewing the page for: <strong>{slug}</strong></p>
