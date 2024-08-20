<script>
	export let status;
	export let error;
</script>

<div class="error-container">
	<div class="error-code">404</div>
	<div class="error-message">Oops! The page you are looking for does not exist.</div>
	<a href="/" class="home-link">Go to Home</a>
</div>

<style>
	.error-container {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		height: 100vh;
		text-align: center;
	}

	.error-code {
		font-size: 8rem;
		font-weight: bold;
		color: #ff4d4d;
	}

	.error-message {
		font-size: 1.5rem;
		color: #333;
	}

	.home-link {
		margin-top: 1rem;
		text-decoration: none;
		color: #007bff;
	}
</style>
