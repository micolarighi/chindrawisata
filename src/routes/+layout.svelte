<script>
	import 'tailwindcss/tailwind.css';
	import Navbar from './components/Navbar.svelte';
	import Footer from './components/Footer.svelte';
</script>

<nav>
	<Navbar />
</nav>
<slot />
<footer>
	<Footer />
</footer>
