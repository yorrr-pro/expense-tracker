<script>
	import favicon from '$lib/assets/favicon.svg';
	import "../app.css";
	import { Button } from "$lib/components/ui/button.svelte";

	let { children } = $props();
</script>

<!-- <svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head> -->

<div id="navigation">
	<nav>
	  <p>hello</p>

	</nav>
</div>
<!-- 
<Button variant="outline">
  Click me
</Button> -->
<button>
	 hel
</button>

<div>
	dfdfs
</div>


<style>

    div{
	background-color:blue;
	}

</style>

{@render children()}
