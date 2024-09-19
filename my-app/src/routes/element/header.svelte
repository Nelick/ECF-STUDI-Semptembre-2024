<script>
</script>

<div class="section">
	<div class="container">
		<b class="title">Bienvenue sur GameStore</b>
		<div class="description">
			Gamestore : Le jeu vidéo à portée de main. Conseils personnalisés et large choix de jeux dans
			nos 5 magasins.
		</div>
		<div class="input">
			<div class="textfield">
				<div class="text">Search for your favorite games</div>
			</div>
		</div>
		<div class="button">
			<div class="primary">
				<div class="title1">Explore Now</div>
			</div>
		</div>
	</div>
	<img class="section-child" alt="" src="Vector 200.svg" />
</div>

<style>
	.title {
  	width: 32.5rem;
  	position: relative;
  	font-size: 2.5rem;
  	line-height: 3rem;
  	display: inline-block;
  	text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
}
.description {
  	width: 32.5rem;
  	position: relative;
  	line-height: 1.5rem;
  	display: inline-block;
  	text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
}
.text {
  	flex: 1;
  	position: relative;
  	line-height: 1.25rem;
  	display: inline-block;
  	overflow: hidden;
  	text-overflow: ellipsis;
  	white-space: nowrap;
  	height: 1.25rem;
}
.textfield {
  	align-self: stretch;
  	border-radius: 6px;
  	background-color: var(--color-white);
  	border: 1px solid rgba(0, 0, 0, 0.1);
  	display: flex;
  	flex-direction: row;
  	align-items: center;
  	justify-content: flex-start;
  	padding: 0.5rem var(--padding-xs);
}
.input {
  	width: 22.5rem;
  	overflow: hidden;
  	display: flex;
  	flex-direction: column;
  	align-items: flex-start;
  	justify-content: center;
  	text-align: left;
  	font-size: 0.875rem;
  	color: rgba(0, 0, 0, 0.5);
}
.title1 {
  	position: relative;
  	line-height: 1.5rem;
  	font-weight: 500;
}
.primary {
  	width: 15rem;
  	border-radius: 8px;
  	background-color: #000;
  	display: flex;
  	flex-direction: column;
  	align-items: center;
  	justify-content: center;
  	padding: var(--padding-xs);
  	box-sizing: border-box;
}
.button {
  	overflow: hidden;
  	display: flex;
  	flex-direction: column;
  	align-items: flex-start;
  	justify-content: flex-start;
  	text-align: left;
}
.container {
  	flex: 1;
  	display: flex;
  	flex-direction: column;
  	align-items: center;
  	justify-content: flex-start;
  	gap: 1.5rem;
  	z-index: 0;
}
.section-child {
  	width: 100%;
  	position: absolute;
  	margin: 0 !important;
  	right: 0rem;
  	bottom: -0.031rem;
  	left: 0rem;
  	max-width: 100%;
  	overflow: hidden;
  	max-height: 100%;
  	z-index: 1;
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
