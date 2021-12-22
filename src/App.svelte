<script>
	import Card from "./Card.svelte";
	const body = `
		<h3>Mentionnez les thèmes de la vidéo.</h3>
		<p>
		Les croissants et la culture française.
		</p>
		<h3>Résumez la vidéo en un paragraphe.</h3>
		<p>
		Dans cette vidéo, le présentateur Jamy raconte l'histoire d'origine du croissant.
		</p>
		<h3>Rappelez les points principaux (les arguments de l’auteur) sous forme de plan.</h3>
		<p>
		- Introduction
		- L'histoire des croissants
			- quand, quoi, où
			- ottomans assiège Vienne
			- boulangers les repèrent
			- donc le croissant est inventé!
		- mais c'est seulement une histoire (pas vrai)
		- server les croissant dans les cérémonies réligieux
		</p>
		<h3>
		Faites le bilan : Que pensez-vous de cette vidéo, avez-vous appris des choses nouvelles (développez)?
		</h3>
		<p>
		J'ai pensé que cette vidéo est intéressant. J'ai aimé l'histoire que Jamy a raconté parce que ça montre que les choses ordinaires ont des histoires extraordinaires. Après j'ai regardé la vidéo, j'ai aussi un peu faim.
		</p>
	`
</script>

<body>
	<main>
		<h1>
			mon blog de français.
		</h1>
		<hr class="solid">
	</main>
	<Card title="Hello" body={body}></Card>
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