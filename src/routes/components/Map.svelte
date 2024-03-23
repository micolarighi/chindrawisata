<div class="mapouter">
	<div class="gmap_canvas">
		<!-- svelte-ignore a11y-missing-attribute -->
		<iframe
			class="gmap_iframe"
			frameborder="0"
			scrolling="no"
			marginheight="0"
			marginwidth="0"
			src="https://maps.google.com/maps?width=1000&amp;height=400&amp;hl=en&amp;q=Chindrawisata Tours&amp;t=&amp;z=14&amp;ie=UTF8&amp;iwloc=B&amp;output=embed"
		></iframe><a href="https://strandsgame.net/">Strands Game</a>
	</div>
	<style>
		.mapouter {
			position: relative;
			text-align: right;
			width: 1000px;
			height: 400px;
		}
		.gmap_canvas {
			overflow: hidden;
			background: none !important;
			width: 1000px;
			height: 400px;
		}
		.gmap_iframe {
			width: 1000px !important;
			height: 400px !important;
		}
		@media (max-width: 600px) {
			.gmap_iframe {
				width: 300px !important;
				height: 400px !important;
			}
			.gmap_canvas {
				overflow: hidden;
				background: none !important;
				width: 300px;
				height: 400px;
			}
			.mapouter {
				position: relative;
				text-align: right;
				width: 300px;
				height: 400px;
			}
		}
	</style>
</div>
