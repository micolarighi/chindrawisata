<script>
	import Navbar from './components/Navbar.svelte';
	import Hero from './components/Hero.svelte';
	import BookSection from './components/BookSection.svelte';
</script>

<main class="container px-8 md:px-24">
	<Navbar />
	<Hero />
	<BookSection />
	<h1>Welcome to SvelteKit</h1>
	<button class="btn btn-primary">Test</button>
	<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
</main>
