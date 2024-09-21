<script>
</script>

<div class="products">
	<div class="container">
		<div class="container1">
			<b class="title">Tendance du moment : découvrez nos nouveautés.</b>
			<div class="description">Découvrez nos jeux vidéo les plus innovants !</div>
		</div>
		<div class="image-container">
			<img class="image-icon" alt="" src="background 2.jpeg" />
		</div>
	</div>
	<div class="list">
		<div class="row">
			<div class="card">
				<div class="image-container1">
					<div class="image">
						<img class="image-container1" alt="jeux indi" src="Pixel_travler.jpeg" />
						<div class="tag">
							<div class="text">New</div>
						</div>
					</div>
				</div>
				<div class="text-content">
					<div class="title2">The Pixel Traveler</div>
					<div class="subtitle">Date de sortie : Mars 2025 !</div>
				</div>
			</div>
			<div class="card1">
				<div class="image-container1">
					<div class="image">
						<img class="image-container1" alt="indi game" src="Zelgts_game.jpeg" />
						<div class="tag1">
							<div class="text">Popular</div>
						</div>
					</div>
				</div>
				<div class="text-content1">
					<div class="title2">Zelgts</div>
					<div class="subtitle">Date de Sortie : Décembre 2024 !</div>
				</div>
			</div>
			<div class="card1">
				<div class="image-container1">
					<div class="image">
						<img class="image-container1" alt="indi game" src="pixel_csgo.jpeg" />
						<div class="title3">Game Cover</div>
						<div class="tag2">
							<div class="text">Classic</div>
						</div>
					</div>
				</div>
				<div class="text-content1">
					<div class="title2">Pixel Global Offensive</div>
					<div class="subtitle-wrapper">
						<div class="subtitle2">19.99 EUR</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</div>

<style>
	:global(body) {
		margin: 0;
		line-height: normal;
	}
	:global(:root) {
		/* fonts */
		--font-roboto: Roboto;
		/* font sizes */
		--font-size-xl: 1.25rem;
		--font-size-base: 1rem;
		--font-size-xs: 0.75rem;
		/* Colors */
		--color-gray-100: rgba(0, 0, 0, 0.05);
		--color-gray-200: rgba(0, 0, 0, 0.1);
		--color-black: #000;
		--color-white: #fff;
		/* Gaps */
		--gap-41xl: 3.75rem;
		--gap-9xs: 0.25rem;
		/* Paddings */
		--padding-xs: 0.75rem;
		--padding-9xs: 0.25rem;
		--padding-5xs: 0.5rem;
		/* Border radiuses */
		--br-7xs: 6px;
	}
	.title {
		align-self: stretch;
		position: relative;
		line-height: 3rem;
		text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
	}
	.description {
		align-self: stretch;
		position: relative;
		font-size: var(--font-size-base);
		line-height: 1.5rem;
		color: var(--color-black);
		text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
	}
	.container1 {
		width: 53, 75rem;
		display: flex;
		flex-direction: column;
		align-items: flex-start;
		justify-content: flex-start;
		gap: 1.5rem;
	}
	.image-icon {
		width: 100%;
		max-height: 100%;
		position: relative;
		object-fit: fill;
		box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
	}
	.image-container {
		width: 11.25rem;
		height: 11.25rem;
		overflow: hidden;
		flex-shrink: 0;
		display: flex;
		flex-direction: row;
		align-items: flex-start;
		justify-content: flex-start;
	}
	.container {
		align-self: stretch;
		display: flex;
		flex-direction: row;
		align-items: center;
		justify-content: center;
		gap: var(--gap-41xl);
		z-index: 0;
	}
	.text {
		position: relative;
		line-height: 1rem;
		font-weight: 500;
	}
	.tag {
		position: absolute;
		top: 0rem;
		left: 0rem;
		border-radius: var(--br-7xs) 0px var(--br-7xs) 0px;
		background-color: var(--color-gray-100);
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		padding: var(--padding-9xs) var(--padding-5xs);
		text-align: left;
	}
	.image {
		align-self: center;
		flex: 1;
		position: relative;
		background-image: url('image.png');
		background-size: cover;
		background-repeat: no-repeat;
		background-position: top;
	}
	.image-container1 {
		align-self: stretch;
		max-height: auto;
		width: 100%;
		overflow: hidden;
		flex-shrink: 0;
		display: flex;
		flex-direction: row;
		align-items: flex-start;
		justify-content: flex-start;
	}
	.title2 {
		align-self: stretch;
		position: relative;
		line-height: 1.5rem;
	}
	.subtitle {
		align-self: stretch;
		position: relative;
		font-size: var(--font-size-xl);
		line-height: 1.75rem;
		font-weight: 500;
	}
	.text-content {
		align-self: stretch;
		display: flex;
		flex-direction: column;
		align-items: flex-start;
		justify-content: flex-start;
		padding: var(--padding-xs);
		gap: var(--gap-9xs);
		text-align: left;
		font-size: var(--font-size-base);
		color: var(--color-black);
	}
	.card {
		flex: 1;
		box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
		border-radius: var(--br-7xs);
		border: 1px solid var(--color-gray-200);
		overflow: hidden;
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: flex-start;
		color: var(--color-white);
		transition:
			transform 0.3s ease,
			box-shadow 0.3s ease;
	}
	.card:hover {
		transform: translateY(-10px);
		box-shadow:
			0 4px 8px rgba(0, 0, 0, 0.2),
			0 0 10px rgba(255, 255, 255, 0.5); /* Ajout de l'effet de surbrillance */
	}
	.title3 {
		position: absolute;
		width: calc(100% - 32px);
		top: calc(50% - 8px);
		left: 1rem;
		line-height: 1rem;
		display: none;
		align-items: center;
		justify-content: center;
		height: 1rem;
	}
	.tag1 {
		position: absolute;
		top: 0rem;
		left: 0rem;
		border-radius: var(--br-7xs) 0px var(--br-7xs) 0px;
		background-color: var(--color-gray-100);
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		padding: var(--padding-9xs) var(--padding-5xs);
		text-align: left;
		color: rgba(255, 255, 255, 0.8);
	}
	.text-content1 {
		align-self: stretch;
		display: flex;
		flex-direction: column;
		align-items: flex-start;
		justify-content: flex-start;
		padding: var(--padding-xs);
		gap: var(--gap-9xs);
		text-align: left;
		font-size: var(--font-size-base);
	}
	.card1 {
		flex: 1;
		box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
		border-radius: var(--br-7xs);
		border: 1px solid var(--color-gray-200);
		overflow: hidden;
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: flex-start;
		transition:
			transform 0.3s ease,
			box-shadow 0.3s ease;
	}
	.card1:hover {
		transform: translateY(-10px);
		box-shadow:
			0 4px 8px rgba(0, 0, 0, 0.2),
			0 0 10px rgba(255, 255, 255, 0.5); /* Ajout de l'effet de surbrillance */
	}
	.tag2 {
		position: absolute;
		top: 0rem;
		left: 0rem;
		border-radius: var(--br-7xs) 0px var(--br-7xs) 0px;
		background-color: var(--color-gray-100);
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		padding: var(--padding-9xs) var(--padding-5xs);
		text-align: left;
		color: var(--color-white);
	}
	.subtitle2 {
		width: 7.75rem;
		position: relative;
		line-height: 1.75rem;
		font-weight: 500;
		white-space: pre-wrap;
		display: inline-block;
		flex-shrink: 0;
	}
	.subtitle-wrapper {
		display: flex;
		flex-direction: row;
		align-items: center;
		justify-content: center;
		font-size: var(--font-size-xl);
	}
	.row {
		align-self: stretch;
		display: flex;
		flex-direction: row;
		align-items: flex-start;
		justify-content: flex-start;
		gap: 2.5rem;
	}
	.list {
		align-self: stretch;
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		z-index: 1;
		text-align: center;
		font-size: var(--font-size-xs);
		color: var(--color-black);
	}

	.products {
		width: 100%;
		position: relative;
		box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
		overflow: hidden;
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		padding: 3.75rem 10.625rem;
		box-sizing: border-box;
		gap: var(--gap-41xl);
		text-align: left;
		font-size: 2.5rem;
		color: var(--color-white);
		font-family: var(--font-roboto);
	}
</style>
