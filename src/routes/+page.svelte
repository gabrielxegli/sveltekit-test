<script>
	import '../app.css';
</script>

<h1 class="testpage">Test Page</h1>

<style>
	.testpage {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100vh;
		font-size: 75px;
		font-family: Arial, Helvetica, sans-serif;
	}

	@media (prefers-color-scheme: dark) {
		.testpage {
			background: #2d2d2d;
			color: aliceblue;
			outline: 5px dashed #000;
		}
	}
</style>
