<style>
	/* Mobile First CSS */
	.container {
		display: flex;
		height: calc(100vh - 50px);
	}

	.item {
		display: flex;
		flex-direction: column;
	}

	.sidebar {
		background-color: blue;
		width: 100px;

	}

	.toggle {
		margin-top: auto;
    	align-self: flex-start;
	}

	.main {
		background-color: violet;
		flex: 3;
	}

	/* Tablet */
	@media (min-width: 600px) {

	}

	/* Desktop */
	@media (min-width: 1025px) {
		
	}
</style>

<svelte:head>
	<title>Flexbox Guide</title>
</svelte:head>

<div class="container">
	<div class="item sidebar">
		<h1>Flexbox Guide</h1>

		<div class="toggle">
			<button type="button">M</button>
		</div>
	</div>
	<div class="item main">
		<p>main content goes here you!</p>
	</div>
</div>

