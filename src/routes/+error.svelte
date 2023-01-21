<script>
	// @ts-nocheck
	import { page } from '$app/stores';
</script>

<section>
	<h1>{$page.status}: {$page.error.message}</h1>
</section>

<style>
	@import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:wght@100&display=swap');

	h1 {
		font-family: 'IBM Plex Mono', monospace;
		font-size: 13vh;
	}

	section {
		padding: 3px;
		color: rgb(47, 56, 76);
		display: flex;
		justify-content: center;
	}
</style>
