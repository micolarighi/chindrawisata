<script>
	import Icon from '@iconify/svelte';
</script>

<div class="text-center my-16 bg-zinc-100 px-8 md:px-24 py-12">
	<h1 class="md:text-4xl text-2xl font-bold">Kenapa Memilih Kami?</h1>
	<p class="text-gray-400 mb-8 mt-2 leading-none">
		Jalankan Tour yang Aman, Terpercaya & Menyenangkan bersama Chindra Wisata
	</p>
	<div class="grid grid-cols-1 md:grid-cols-3 gap-6">
		<div class="card bg-base-100 shadow-xl">
			<div class="text-center flex justify-center mt-5">
				<Icon icon="solar:tag-price-bold" class="text-6xl text-lime-400" />
			</div>
			<div class="card-body">
				<h2 class="text-2xl font-bold text-center">Harga Terjangkau</h2>
				<p>Dapatkan harga paket perjalanan murah dengan penawaran menarik.</p>
				<div class="card-actions justify-end"></div>
			</div>
		</div>
		<div class="card bg-base-100 shadow-xl">
			<div class="text-center flex justify-center mt-5">
				<Icon icon="fa6-solid:handshake" class="text-6xl text-lime-400" />
			</div>
			<div class="card-body">
				<h2 class="text-2xl font-bold text-center">Terpercaya</h2>
				<p>Mendapatkan kepercayaan dari konsumen yang memilih kami.</p>
				<div class="card-actions justify-end"></div>
			</div>
		</div>
		<div class="card bg-base-100 shadow-xl">
			<div class="text-center flex justify-center mt-5">
				<Icon icon="mdi:email-fast" class="text-6xl text-lime-400" />
			</div>
			<div class="card-body">
				<h2 class="text-2xl font-bold text-center">Pemesanan Mudah</h2>
				<p>Sistem pemesanan yang mudah dengan proses yang sederhana.</p>
				<div class="card-actions justify-end"></div>
			</div>
		</div>
	</div>
</div>
