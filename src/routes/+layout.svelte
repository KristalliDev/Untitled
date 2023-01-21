<nav>
	<div class="navbar">
		<a class="link" href="/">Home</a>
		<a class="link" href="/about">About</a>
		<a class="link" href="/blog">Blog</a>
		<a class="link" href="/contact">Contact</a>
	</div>
</nav>

<slot />

<style>
@import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Mono&display=swap');

.link {
    text-decoration: none;
    color:rgb(76, 85, 112);
	font-family: 'IBM Plex Mono', monospace;
}

:hover.link {
    color: rgb(22, 28, 49);
}

.navbar {
	display: flex;
	justify-content: space-evenly;
	padding: 1rem;
	font-size: 3vh;
}

@media screen and (max-width: 600px) {
	.navbar {
		font-size: 2.5vh;
		padding: 0.5rem;
		}
	}
</style>