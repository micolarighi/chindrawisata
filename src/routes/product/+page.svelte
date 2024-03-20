<script>
	import Hero from '../components/Hero.svelte';
	import Card from '../components/Card.svelte';
	import Footer from '../components/Footer.svelte';
</script>

<main>
	<div class="grid grid-cols-1 md:grid-cols-3 px-8 md:px-24">
		<Card
			img={'/src/lib/assets/product/umrah-desember.jpeg'}
			title={'Umrah Akhir Tahun'}
			desc={'Umrah Akhir Tahun Desember 2022'}
			link={'/product/paket_1'}
		/>
	</div>
</main>
