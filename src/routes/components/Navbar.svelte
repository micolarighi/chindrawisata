<script>
	import logo from '$lib/assets/logo.png';
	import { page } from '$app/stores';

	$: routeId = $page.route.id;
</script>

<div class="navbar bg-base-100">
	<div class="navbar-start">
		<div class="dropdown">
			<div tabindex="0" role="button" class="btn btn-ghost lg:hidden">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					class="h-5 w-5"
					fill="none"
					viewBox="0 0 24 24"
					stroke="currentColor"
					><path
						stroke-linecap="round"
						stroke-linejoin="round"
						stroke-width="2"
						d="M4 6h16M4 12h8m-8 6h16"
					/></svg
				>
			</div>
			<ul class="menu menu-sm dropdown-content mt-3 z-[1] p-2 shadow bg-base-100 rounded-box w-52">
				<li><a class:text-lime-400={routeId == '/'} href="">Home</a></li>
				<li><a class:text-lime-400={routeId == '/product'} href="">Paket</a></li>
				<li><a class:text-lime-400={routeId == 'gallery'} href="">Gallery</a></li>
				<li><a class:text-lime-400={routeId == 'about'} href="">About</a></li>
				<li><a class:text-lime-400={routeId == 'contact'} href="">Contact</a></li>
			</ul>
		</div>
		<a href="/"><img width="200" src={logo} alt="Logo Chindrawisata" /></a>
	</div>
	<div class="navbar-center hidden lg:flex">
		<ul class="menu menu-horizontal px-1 text-lg">
			<li class:active={routeId == '/'} id="home"><a href="/">Home</a></li>
			<li class:active={routeId == '/product'} id="about"><a href="/product">Paket</a></li>
			<li class:active={routeId == 'gallery'} id="gallery"><a href="">Gallery</a></li>
			<li class:active={routeId == 'about'} id="about"><a href="">About</a></li>
			<li class:active={routeId == 'contact'} id="contact"><a href="">Contact</a></li>
		</ul>
	</div>
	<div class="navbar-end">
		<a class="btn bg-lime-400">Pesan Sekarang</a>
	</div>
</div>

<style>
	.active {
		color: #84cc16;
		font-weight: bold;
	}
</style>
