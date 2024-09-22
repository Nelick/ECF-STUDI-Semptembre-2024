<script>
</script>

<div class="contents">
	<div class="container">
		<div class="image-container">
			<img class="image-icon" alt="" src="shop.jpeg" />
		</div>
		<div class="container1">
			<b class="title">Actualité</b>
			<div class="description">
				Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla eget tortor convallis, congue
				nulla vitae, facilisis orci. Vestibulum dolor urna, efficitur sed ipsum non, scelerisque
				auctor felis. Etiam bibendum, purus et cursus porttitor, turpis augue placerat nulla, sed
				luctus metus dolor a neque. Pellentesque habitant morbi tristique senectus et netus et
				malesuada fames ac turpis egestas
			</div>
		</div>
	</div>
	<div class="list">
		<div class="row">
			<div class="article1">
				<div class="image-container1">
					<img class="image-icon" alt="image_magasin" src="shop3.jpeg" />
				</div>
				<div class="title-parent">
					<div class="title1">Évènement en Magasin</div>
					<div class="subtitle">Découvre Les dernier évènement chez nous !</div>
					<div class="selection">
						<div class="label-normal">
							<div class="label-text">New Releases</div>
						</div>
					</div>
					<div class="user">
						<div class="avatar">
							<div class="avatar1"></div>
							<div class="title-wrapper">
								<div class="title2">Gaming Guru</div>
							</div>
						</div>
					</div>
				</div>
			</div>
			<div class="article1">
				<div class="image-container1">
					<img class="image-icon" alt="" src="shop2.png" />
				</div>
				<div class="title-parent">
					<div class="title3">Les dernier Jeux Tester !</div>
					<div class="subtitle1">
						Découvre les dernier recommandation de joueur de la Boutique !
					</div>
					<div class="selection">
						<div class="label-normal">
							<div class="label-text">Interviews</div>
						</div>
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
	:global(root) {
		/* fonts */
		--font-roboto: Roboto;
		/* font sizes */
		--font-size-xs: 0.75rem;
		--font-size-base: 1rem;
		--font-size-xl: 1.25rem;
		/* Colors */
		--color-gray-100: rgba(0, 0, 0, 0.1);
		--color-gainsboro-100: rgba(217, 217, 217, 0.5);
		--color-black: #000;
		/* Gaps */
		--gap-41xl: 3.75rem;
		--gap-base: 1rem;
		--gap-5xs: 0.5rem;
		/* Paddings */
		--padding-base: 1rem;
		--padding-9xs: 0.25rem;
		--padding-11xs: 0.125rem;
		/* Border radiuses */
		--br-7xs: 6px;
		--br-11xs: 2px;
	}

	.image-icon {
		margin: var(--gap-5xs);
		align-self: stretch;
		flex: 1;
		position: relative;
		max-width: 100%;
		overflow: hidden;
		max-height: 100%;
		object-fit: cover;
	}
	.image-container {
		width: 11.25rem;
		height: 11.25rem;
		overflow: hidden;
		flex-shrink: 0;
		display: flex;
		text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.4);
	}

	.title {
		align-self: stretch;
		position: relative;
		line-height: 3rem;
		text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
	}
	.description {
		margin-right: 5rem;
		font-family: 'Roboto', sans-serif;
		align-self: stretch;
		position: relative;
		font-size: var(--font-size-base);
		letter-spacing: 0.1em;
		color: var(--color-black);
	}
	.container1 {
		width: 53.75rem;
		display: flex;
		flex-direction: column;
		align-items: flex-start;
		justify-content: flex-start;
		gap: 2.5rem;
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

	.image-container1 {
		width: 6.25rem;
		height: 6.25rem;
		overflow: hidden;
		flex-shrink: 0;
		display: flex;
		flex-direction: row;
		align-items: flex-start;
		justify-content: flex-start;
		background-image: url('image container.png');
		background-size: cover;
		background-repeat: no-repeat;
		background-position: top;
		text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
	}
	.title1 {
		align-self: stretch;
		position: relative;
		line-height: 1.75rem;
		font-weight: 500;
		color: rgba(0, 0, 0, 0.81);
		text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
		padding-left: 2rem;
		padding-top: 1rem;
	}
	.subtitle {
		align-self: stretch;
		position: relative;
		font-size: var(--font-size-base);
		line-height: 1.5rem;
		padding-left: 2rem;
	}
	.label-text {
		position: relative;
		line-height: 1rem;
		font-size: var(--font-size-xs);
	}
	.label-normal {
		border-radius: var(--br-11xs);
		background-color: var(--color-gainsboro-100);
		border: 0.5px solid var(--color-gray-100);
		overflow: hidden;
		display: flex;
		flex-direction: row;
		align-items: center;
		justify-content: center;
		padding: var(--padding-11xs) var(--padding-9xs);
	}
	.selection {
		align-self: stretch;
		overflow: hidden;
		display: flex;
		flex-direction: row;
		align-items: center;
		justify-content: flex-start;
		padding: var(--padding-9xs) 2rem;
		font-size: var(--font-size-xs);
	}
	.avatar1 {
		width: 1.25rem;
		position: relative;
		border-radius: 20px;
		background-color: var(--color-gray-100);
		height: 1.25rem;
		overflow: hidden;
		flex-shrink: 0;
		display: none;
	}
	.title2 {
		width: 22.125rem;
		position: relative;
		line-height: 1.25rem;
		font-weight: 500;
		display: none;
		overflow: hidden;
		text-overflow: ellipsis;
		white-space: nowrap;
		
	}
	.title-wrapper {
		flex: 1;
		height: 1.25rem;
		display: flex;
		flex-direction: column;
		align-items: flex-start;
		justify-content: flex-start;
	}
	.avatar {
		flex: 1;
		display: flex;
		flex-direction: row;
		align-items: center;
		justify-content: flex-start;
		gap: var(--gap-5xs);
		text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
	}
	.user {
		align-self: stretch;
		display: flex;
		flex-direction: row;
		align-items: center;
		justify-content: flex-start;
		padding: var(--padding-9xs) 0rem;
		font-size: 0.875rem;
	}
	.title-parent {
		flex: 1;
		display: flex;
		flex-direction: column;
		align-items: flex-start;
		justify-content: flex-start;
		gap: var(--gap-5xs);
	}

	.title3 {
		align-self: stretch;
		position: relative;
		line-height: 1.75rem;
		font-weight: 500;
		color: rgba(0, 0, 0, 0.8);
		text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
		padding-left: 2rem;
		padding-top: 1rem;
	}
	.subtitle1 {
		align-self: stretch;
		position: relative;
		font-size: var(--font-size-base);
		line-height: 1.5rem;
		text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
		padding-left: 2rem;
	}
	.article1 {
		flex: 1;
		border-radius: var(--br-7xs);
		border: 1px solid var(--color-gray-100);
		box-sizing: border-box;
		height: 10.25rem;
		display: flex;
		flex-direction: row;
		align-items: flex-start;
		justify-content: center;
		padding: var(--padding-base);
		gap: var(--gap-base);
	}
	.row {
		align-self: stretch;
		display: flex;
		flex-direction: row;
		align-items: center;
		justify-content: flex-start;
		gap: 2.5rem;
	}
	.list {
		align-self: stretch;
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		padding: 1.25rem 0rem;
		z-index: 1;
		font-size: var(--font-size-xl);
		color: var(--color-black);
	}

	.contents {
		width: 100%;
		position: relative;
		box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
		height: 36.875rem;
		overflow: hidden;
		flex-shrink: 0;
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		padding: 3.75rem 10.625rem;
		box-sizing: border-box;
		gap: var(--gap-41xl);
		text-align: left;
		font-size: 2.5rem;
		color: #fff;
		font-family: var(--font-roboto);
	}
</style>
