
<script lang="ts">
	let { title, description, videoSrc, poster } = $props();
</script>

<div class="video-comp">
	<div class="video-title-desc">
		<h2>{title}</h2>
		<p class="video-description">{description}</p>
	</div>
	<div class="card-nobackdrop video-card">
		<video controls poster={poster} src={videoSrc}>
			<track kind="captions" />
		</video>
	</div>
</div>
