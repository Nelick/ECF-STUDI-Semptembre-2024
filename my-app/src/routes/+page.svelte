<script>
	import Navbar from './element/navbar.svelte';
	import Header from './element/header.svelte';
	import Product from './element/product.svelte';
</script>

<div class="container">
	<div class="navbar">
		<Navbar />
	</div>
	<div class="header">
		<Header />
	</div>
	<div class="product">
		<Product />
	</div>
</div>

<style>
	:global(body) {
		font-family: 'Roboto', sans-serif;
		background-image: url('gamestore-background.PNG.jpeg');
		padding-top: 5em;
		margin: 0;
		line-height: normal;
		background-size: cover;
		background-position: center;
		background-repeat: no-repeat;
	}
	:global(:root) {
		--font-roboto: var(--font-roboto);
		--font-size: 1rem;
	}
</style>
