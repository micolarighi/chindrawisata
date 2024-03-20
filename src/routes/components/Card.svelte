<script>
	export let title;
	export let desc;
	export let img;
	export let alt;
	export let link;
</script>

<div class="card bg-base-100 shadow-xl mt-12">
	<figure>
		<img src={img} {alt} />
	</figure>
	<div class="card-body">
		<h2 class="card-title">{title}</h2>
		<p>{desc}</p>
		<div class="card-actions justify-start">
			<a href={link} class="btn">Selengkapnya</a>
			<button class="btn bg-lime-400">Pesan Sekarang</button>
		</div>
	</div>
</div>
