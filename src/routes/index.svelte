<script>
	import products from '$lib/listing.js';
	let name = 'Romain';
</script>


<section>
	<p>Bonjour {name}</p>
	{products}
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 1;
	}
</style>
