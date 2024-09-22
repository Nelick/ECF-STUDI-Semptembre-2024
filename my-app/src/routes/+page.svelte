<script>
	import Navbar from './element/navbar.svelte';
	import Header from './element/header.svelte';
	import Product from './element/product.svelte';
	import Contents from './element/contents.svelte';
	import Footer from './element/footer.svelte';
	import  Actu from './element/page/actualite.svelte';
</script>

<div class="container">
	<div class="navbar">
		<Navbar />
	</div>
	<div class="header fade-in">
		<Header />
	</div>
	<div class="product">
		<Product />
	</div>
	<div class="contents">
		<Contents />
	</div>
	<div class="footer">
		<Footer />
	</div>
</div>

<style>
	@keyframes fadeIn {
		from {
			opacity: 0;
		}
		to {
			opacity: 1;
		}
	}

	.fade-in {
		animation: fadeIn 2s ease-in;
	}
	:global(body) {
		font-family: 'Roboto', sans-serif;
		background-image: url('gamestore-background.PNG.jpeg');
		padding-top: 5em;
		margin: 0;
		line-height: normal;
		background-size: cover;
		background-position: center;
		background-repeat: no-repeat;
		scroll-behavior: smooth;
	}
	:global(:root) {
		--font-roboto: var(--font-roboto);
		--font-size: 1rem;
	}
	@media (max-width: 1200px) {
		:global(body) {
			font-size: 0.9rem;
		}
		.container {
			padding: 0 1rem;
		}
	}

	@media (max-width: 992px) {
		:global(body) {
			font-size: 0.8rem;
		}
		.container {
			padding: 0 0.5rem;
		}
	}

	@media (max-width: 768px) {
		:global(body) {
			font-size: 0.7rem;
		}
		.container {
			flex-direction: column;
			padding: 0;
		}
		.navbar,
		.header,
		.product,
		.contents {
			width: 100%;
		}
	}

	@media (max-width: 576px) {
		:global(body) {
			font-size: 0.6rem;
		}
		.container {
			padding: 0;
		}
		.navbar,
		.header,
		.product,
		.contents {
			width: 100%;
			padding: 0.5rem;
		}
	}
</style>
