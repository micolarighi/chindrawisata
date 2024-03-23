<script>
	import Hero from '../components/Hero.svelte';
	import Card from '../components/Card.svelte';
	import Footer from '../components/Footer.svelte';

	import Paket1 from '$lib/assets/product/umrah.webp';
	import Paket2 from '$lib/assets/product/turkey.webp';
	import Paket3 from '$lib/assets/product/aqsa.webp';
</script>

<main>
	<h1 class="text-center text-4xl font-bold mt-12">Pilihan Paket Perjalanan</h1>
	<div class="grid grid-cols-1 md:grid-cols-3 px-8 gap-12 md:px-24">
		<Card
			img={Paket1}
			title={'Paket Umrah'}
			desc={'Umrah Akhir Tahun Desember 2024'}
			link={'/product/paket_1'}
		/>
		<Card
			img={Paket2}
			title={'Paket Turkey'}
			desc={'Perjalanan menuju negara Turkey'}
			link={'/product/paket_2'}
		/>
		<Card
			img={Paket3}
			title={'Tour Aqsa'}
			desc={'Tour ke masjid Al-Aqsa'}
			link={'/product/paket_3'}
		/>
	</div>
</main>
