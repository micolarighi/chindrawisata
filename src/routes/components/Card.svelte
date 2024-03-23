<script>
	export let title;
	export let desc;
	export let img;
	export let alt;
	export let link;
	import BookBtn from './BookBtn.svelte';
</script>

<div class="card bg-base-100 shadow-xl mt-12">
	<figure>
		<img src={img} {alt} />
	</figure>
	<div class="card-body">
		<h2 class="card-title">{title}</h2>
		<p>{desc}</p>
		<div class="card-actions justify-center">
			<a href={link} class="btn w-full text-xs md:text-md">Selengkapnya</a>
			<BookBtn width={'full'} />
		</div>
	</div>
</div>
