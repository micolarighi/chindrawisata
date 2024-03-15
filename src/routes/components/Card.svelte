<script>
	export let title;
	export let desc;
	export let img;
	export let alt;
</script>

<div class="card w-96 bg-base-100 shadow-xl">
	<figure>
		<img src={img} {alt} />
	</figure>
	<div class="card-body">
		<h2 class="card-title">{title}</h2>
		<p>{desc}</p>
		<div class="card-actions justify-start">
			<button class="btn">Selengkapnya</button>
			<button class="btn bg-lime-400">Pesan Sekarang</button>
		</div>
	</div>
</div>
