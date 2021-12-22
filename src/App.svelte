<script>
	import Card from "./Card.svelte";
		
</script>

<body>
	<main>
		<h1>
			mon blog de français.
		</h1>
		<hr class="solid">
	</main>
	<Card title="🥐 D'où vient le croissant ?"></Card>
</body>

<style>
	main {
		text-align: center;
		padding: 1em;
		top: 40px;
		margin: 0 auto;
	}

	h1 {
		color: #ffffff;
		text-align: center;
	}

	hr.solid {
  	border-top: 2px solid #ffffff;
	}
</style>