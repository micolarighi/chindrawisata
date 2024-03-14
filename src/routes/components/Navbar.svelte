<script>
	import logo from '$lib/assets/logo.png';
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
				<li><a href="">Home</a></li>
				<li><a href="">Produk</a></li>
				<li><a href="">Gallery</a></li>
				<li><a href="">About</a></li>
				<li><a href="">Contact</a></li>
			</ul>
		</div>
		<a href="/"><img width="200" src={logo} alt="Logo Chindrawisata" /></a>
	</div>
	<div class="navbar-center hidden lg:flex">
		<ul class="menu menu-horizontal px-1 text-lg">
			<li><a href="">Home</a></li>
			<li><a href="/product">Produk</a></li>
			<li><a href="">Gallery</a></li>
			<li><a href="">About</a></li>
			<li><a href="">Contact</a></li>
		</ul>
	</div>
	<div class="navbar-end">
		<a class="btn bg-lime-400">PESAN SEKARANG</a>
	</div>
</div>
