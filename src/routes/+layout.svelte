<script lang="ts">
	import './styles.css';
	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><text y='.9em' font-size='80'>🦆</text></svg>" />
</svelte:head>

<header>
	<nav>
		<span class="navbar_logo">&ltcdrezen/&gt</span>
		<div class="navbar_list">
			<a class="navbar_link" href="/">
				Hello
			</a>
			<a class="navbar_link" href="#projects">
				Projects
			</a>
			<a class="navbar_link" href="#contact">
				Contact
			</a>
		</div>
	</nav>
</header>


<app-root>
{@render children()}
</app-root>