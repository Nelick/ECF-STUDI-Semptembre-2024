<script>
	import Navbar from './element/navbar.svelte';
	import Header from './element/header.svelte';
</script>

<div class="container">
	<div class="navbar">
		<Navbar />
	</div>
	<div class="header">
		<Header />
	</div>
</div>

<style>
	.container {
    padding: 5em;
		background-image: url('gamestore-background.jpeg');
		margin: 0;
		line-height: normal;
		background-size: cover;
		background-position: center;
		background-repeat: no-repeat;
	}
</style>
