<script>
	import 'tailwindcss/tailwind.css';
	import Navbar from './components/Navbar.svelte';
	import Footer from './components/Footer.svelte';
	import WhatsappBtn from './components/WhatsappBtn.svelte';
</script>

<nav class="mb-32">
	<Navbar />
</nav>
<WhatsappBtn />
<slot />
<footer>
	<Footer />
</footer>
