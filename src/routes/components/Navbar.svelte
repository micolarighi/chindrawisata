<script>
	import logo from '$lib/assets/logo.png';
	import { page } from '$app/stores';
	import BookBtn from '../components/BookBtn.svelte';

	$: routeId = $page.route.id;
</script>

<div class="navbar bg-base-100 px-8 md:px-24 fixed top-0 z-50">
	<div class="navbar-center">
		<a href="/"><img width="200" src={logo} alt="Logo Chindrawisata" /></a>
		<div class="dropdown">
			<div tabindex="0" role="button" class="btn btn-ghost lg:hidden">
				<h1 class="bg-lime-400 px-3 py-2 font-normal rounded text-lg">Menu</h1>
			</div>
			<ul class="menu menu-lg dropdown-content mt-3 z-[1] p-2 shadow bg-base-100 rounded-box w-32">
				<li class:active={routeId == '/'} id="home"><a href="/">Home</a></li>
				<li class:active={routeId == '/product'} id="about"><a href="/product">Paket</a></li>
				<li class:active={routeId == '/gallery'} id="gallery"><a href="/gallery">Gallery</a></li>
				<li class:active={routeId == '/about'} id="about"><a href="/about">About</a></li>
				<li class:active={routeId == '/contact'} id="contact"><a href="/contact">Contact</a></li>
			</ul>
		</div>
	</div>
	<div class="navbar-center hidden lg:flex">
		<ul class="menu menu-horizontal px-1 text-lg">
			<li class:active={routeId == '/'} id="home"><a href="/">Home</a></li>
			<li class:active={routeId == '/product'} id="product"><a href="/product">Paket</a></li>
			<li class:active={routeId == '/gallery'} id="gallery"><a href="/gallery">Gallery</a></li>
			<li class:active={routeId == '/about'} id="about"><a href="/about">About</a></li>
			<li class:active={routeId == '/contact'} id="contact"><a href="/contact">Contact</a></li>
		</ul>
	</div>
	<div class="navbar-end hidden md:flex">
		<BookBtn />
	</div>
</div>

<style>
	.active {
		color: #84cc16;
		font-weight: bold;
	}
</style>
