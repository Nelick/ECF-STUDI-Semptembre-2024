<script>
</script>

<div class="section">
	<div class="container">
		<b class="title">Bienvenue sur GameStore</b>
		<div class="description">
			GameStore : Le paradis des gamers ! Retrouvez tous vos jeux préférés dans nos magasins. 5
			villes, 1 passion : le jeu vidéo. Nantes, Lille, Bordeaux, Paris, Toulouse.
		</div>
	</div>
</div>

<style>
	@keyframes gameboy-advance {
		0% {
			color: #fff;
			text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
		}
		50% {
			color: #ffcc00;
			text-shadow: 0px 4px 4px rgba(255, 204, 0, 0.5);
		}
		100% {
			color: #fff;
			text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
		}
	}
	.title {
		width: 32.5rem;
		position: relative;
		font-size: 2.6rem;
		line-height: 3rem;
		display: inline-block;
		font-family: var(--font-roboto);
		color: #fff;
		text-align: center;
		text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
		animation: gameboy-advance 3s infinite;
	}
	.description {
		width: 32.5rem;
		position: relative;
		font-size: 1rem;
		line-height: 1.5rem;
		font-family: var(--font-roboto);
		color: #fff;
		text-align: center;
		display: inline-block;
		text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
	}

	.container {
		height: 100%;
		width: 100%;
		flex: 1;
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: flex-start;
		gap: 3.5rem;
		z-index: 0;
	}

	.section {
		width: 100%;
		position: relative;
		background-color: rgba(0, 0, 0, 0.6);
		height: 18.75rem;
		overflow: hidden;
		flex-shrink: 0;
		display: flex;
		flex-direction: row;
		align-items: center;
		justify-content: center;
		padding: 3.75rem 10.625rem;
		box-sizing: border-box;
		gap: 3.75rem;
		text-align: center;
		font-size: var(--font-size-base);
		color: var(--color-white);
		font-family: var(--font-roboto);
	}
</style>
