<script>
	import Hero from '../components/Hero.svelte';
	import Navbar from '../components/Navbar.svelte';
	import Card from '../components/Card.svelte';
</script>

<main class="container px-8 md:px-24">
	<Navbar />
	<Card
		img={'/src/lib/assets/product/umrah-desember.jpeg'}
		title={'Umrah Akhir Tahun'}
		desc={'Umrah Akhir Tahun Desember 2022'}
	/>
</main>
