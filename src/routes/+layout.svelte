<nav>
	<div class="navbar">
		<a href="/">Home</a>
		<a href="/about">About</a>
		<a href="mailto:kristal.dev@pm.me">Contact</a>
	</div>
</nav>

<slot />

<style>
	a {
		text-decoration: none;
		color: rgb(47, 56, 76);
		font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu,
			Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
	}

	.navbar {
		display: flex;
		justify-content: space-between;
		align-items: center;
		padding: 1rem;
		font-size: 1.5rem;
	}

	@media screen and (max-width: 600px) {
		.navbar {
			font-size: 1.2rem;
			padding: 0.5rem;
		}
	}
</style>
