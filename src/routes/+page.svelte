<script>
	import Hero from './components/Hero.svelte';
	import BookSection from './components/BookSection.svelte';
	import Contact from './components/Contact.svelte';
	import Carousel from './components/Carousel.svelte';
	import Gallery from './components/Gallery.svelte';
	import WhyUs from './components/WhyUs.svelte';
	import Icon from '@iconify/svelte';
</script>

<main>
	<Hero />
	<WhyUs />
	<Gallery>
		<Carousel autoplay="2000">
			<img class="rounded-lg px-1" src="/src/lib/assets/gallery/2.JPG" alt="" />
			<img class="rounded-lg px-1" src="/src/lib/assets/gallery/1.png" alt="" />
			<img class="rounded-lg px-1" src="/src/lib/assets/gallery/3.JPG" alt="" />
			<img class="rounded-lg px-1" src="/src/lib/assets/gallery/4.JPG" alt="" />
			<img class="rounded-lg px-1" src="/src/lib/assets/gallery/5.JPG" alt="" />
			<span class="text-3xl text-white" slot="left-control"
				><Icon icon="icon-park-solid:left-c" /></span
			>
			<span class="text-3xl text-white" slot="right-control"
				><Icon icon="icon-park-solid:right-c" /></span
			>
		</Carousel>
	</Gallery>

	<Contact />
</main>
