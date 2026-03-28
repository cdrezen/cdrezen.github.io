
<script lang="ts">
	let { title, description, videoSrc, poster } = $props();
</script>

<div>
	<div class="video-title-desc">
		<h2>{title}</h2>
		<p class="video-description">{description}</p>
	</div>
	<div class="card-nobackdrop video-container">
		<video controls poster={poster} src={videoSrc}>
			<track kind="captions" />
		</video>
	</div>
</div>
