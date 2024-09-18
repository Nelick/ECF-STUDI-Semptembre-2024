<script>
	import Navbar from './element/navbar.svelte';
</script>

<div class="container">
	<div class="navbar">
		<Navbar />
	</div>
	<div class="main"></div>
</div>

<style>
	.container {
		background-image: url('gamestore-background.jpeg');
		margin: 0;
		line-height: normal;
		background-size: cover;
		background-position: center;
		background-repeat: no-repeat;
	}
</style>
