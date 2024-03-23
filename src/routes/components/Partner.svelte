<script>
	import Carousel from '../components/Carousel.svelte';
	import Partner1 from '$lib/assets/partners/iata.webp';
	import Partner2 from '$lib/assets/partners/kan.webp';
	import Partner3 from '$lib/assets/partners/kemenag.webp';
	import Partner4 from '$lib/assets/partners/waytoumrah.webp';
</script>

<div class="md:px-24 px-8">
	<div class="px-8 md:px-24">
		<div class="text-center mb-8 mt-16">
			<h1 class="md:text-4xl text-2xl font-bold">Partner Chindrawisata</h1>
			<p class="text-gray-400 mt-2">Partner yang bekerja sama dengan kami</p>
		</div>
	</div>
	<div class="grid grid-cols-4 gap-4 items-center md:gap-12">
		<img width="140" src={Partner1} alt="" />
		<img width="160" src={Partner2} alt="" />
		<img width="120" src={Partner3} alt="" />
		<img src={Partner4} alt="" />
	</div>
</div>
