<script>
	import favicon from '$lib/assets/favicon.svg';
	import "../app.css";
	import { Button } from "$lib/components/ui/button";

	let { children } = $props();
</script>
<div id="page">

	<div class="bg-blue-400 h-25">
		<div class="flex justify-between items-center h-full px-4">

			<h1 class="text-black text-3xl">
			Expense Tracker App
			</h1>

			<Button class="bg-blue-700 text-white">
			   dark mode
			</Button>

		</div>


	</div>

	<main class="p-6 bg-blue-200 min-h-screen">
      {@render children()}
    </main>

</div>

<style>
/* @media(max-width:405px){

} */

</style>

