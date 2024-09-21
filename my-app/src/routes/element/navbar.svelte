<script>
</script>

<div class="top-bar">
	<img class="top-bar-child" alt="" src="Rectangle 4137.png" />
	<div class="title">GameStore</div>
	<div class="navigation">
		<div class="tab">Accueille</div>
		<div class="tab">Actualite</div>
		<div class="tab">Jeux</div>
		<div class="tab">Précommande</div>
		<div class="tab">Nouveauté</div>
		<div class="textfield">
			<div class="text">Search in site</div>
			<img class="ic-search-icon" alt="" src="ic-search.svg" />
		</div>
	</div>
</div>

<style>
	.top-bar {
		width: 100%;
		position: absolute;
		margin: 0 !important;
		top: 0px;
		right: -1440px;
		left: 0px;
		box-shadow: 0px 0px 6px rgba(0, 0, 0, 0.12);
		background-color: #fff;
		height: 80px;
		overflow: hidden;
		flex-shrink: 0;
		display: flex;
		flex-direction: row;
		align-items: center;
		justify-content: space-between; /* Adjust spacing between elements */
		padding: 20px;
		box-sizing: border-box;
		gap: 20px;
		text-align: left;
		font-size: 28px;
		color: #000;
		font-family: Roboto;
	}

	.top-bar-child {
		width: 40px;
		height: 40px;
		object-fit: cover;
		border-radius: 100px;
		position: relative;
	}

	.title {
		flex: 1;
		position: relative;
		line-height: 36px;
		font-weight: 500;
	}

	.tab {
		position: relative;
		line-height: 24px;
		transition:
			color 0.3s ease,
			transform 0.3s ease;
	}
	.tab:hover {
		color: #ffcc00;
		transform: translateY(-5px);
	}

	.text {
		flex: 1;
		position: relative;
		line-height: 20px;
	}

	.ic-search-icon {
		width: 20px;
		height: 20px;
		position: relative;
	}

	.textfield {
		width: 200px;
		border-radius: 6px;
		border: 1px solid rgba(0, 0, 0, 0.1);
		box-sizing: border-box;
		display: flex;
		flex-direction: row;
		align-items: center;
		justify-content: flex-end;
		padding: 8px;
		gap: 4px;
		font-size: 14px;
		color: rgba(0, 0, 0, 0.5);
	}

	.navigation {
		display: flex;
		flex-direction: row;
		align-items: center;
		justify-content: center;
		gap: 15px; /* Adjust gap for smaller screens */
		font-size: 16px;
	}
</style>
