<script>
	import Image from './components/Image.svelte';
	import GalleryImg from '$lib/assets/gallery/1.webp';
	import GalleryImg2 from '$lib/assets/gallery/2.webp';
	import GalleryImg3 from '$lib/assets/gallery/3.webp';
	import GalleryImg4 from '$lib/assets/gallery/4.webp';
	import GalleryImg5 from '$lib/assets/gallery/5.webp';
	import GalleryImg6 from '$lib/assets/gallery/6.webp';
	import GalleryImg7 from '$lib/assets/gallery/7.webp';
	import GalleryImg8 from '$lib/assets/gallery/8.webp';
	import GalleryImg9 from '$lib/assets/gallery/9.webp';
	import GalleryImg10 from '$lib/assets/gallery/10.webp';
	import GalleryImg11 from '$lib/assets/gallery/11.webp';
	import GalleryImg12 from '$lib/assets/gallery/12.webp';
</script>

<div class="mt-12 px-8 md:px-24 font-bold">
	<h1 class="text-center text-4xl">Kumpulan Foto Perjalanan</h1>
	<div class="grid grid-cols-1 md:grid-cols-3 mt-12 gap-5">
		<Image src={GalleryImg} />
		<Image src={GalleryImg2} />
		<Image src={GalleryImg3} />
		<Image src={GalleryImg4} />
		<Image src={GalleryImg5} />
		<Image src={GalleryImg6} />
		<Image src={GalleryImg7} />
		<Image src={GalleryImg8} />
		<Image src={GalleryImg9} />
		<Image src={GalleryImg10} />
		<Image src={GalleryImg11} />
		<Image src={GalleryImg12} />
	</div>
</div>
