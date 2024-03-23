<script>
	import Hero from './components/Hero.svelte';
	import BookSection from './components/BookSection.svelte';
	import Contact from './components/Contact.svelte';
	import Carousel from './components/Carousel.svelte';
	import Gallery from './components/Gallery.svelte';
	import WhyUs from './components/WhyUs.svelte';
	import About from './components/About.svelte';
	import Partner from './components/Partner.svelte';

	import Icon from '@iconify/svelte';

	import carousel1 from '$lib/assets/gallery/1.webp';
	import carousel2 from '$lib/assets/gallery/2.webp';
	import carousel3 from '$lib/assets/gallery/3.webp';
	import carousel4 from '$lib/assets/gallery/4.webp';
	import carousel5 from '$lib/assets/gallery/5.webp';
</script>

<main>
	<Hero />
	<About />
	<WhyUs />
	<Partner />
	<Gallery>
		<Carousel autoplay="2000">
			<img class="rounded-lg px-1" src={carousel1} alt="" />
			<img class="rounded-lg px-1" src={carousel2} alt="" />
			<img class="rounded-lg px-1" src={carousel3} alt="" />
			<img class="rounded-lg px-1" src={carousel4} alt="" />
			<img class="rounded-lg px-1" src={carousel5} alt="" />
			<span class="text-3xl text-white" slot="left-control"
				><Icon icon="icon-park-solid:left-c" /></span
			>
			<span class="text-3xl text-white" slot="right-control"
				><Icon icon="icon-park-solid:right-c" /></span
			>
		</Carousel>
	</Gallery>
	<BookSection />
	<Contact />
</main>
