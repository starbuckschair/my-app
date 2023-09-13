<script>
	import { onMount } from 'svelte';

	onMount(() => {
		console.log(window.location);
	});
</script>

<nav class="mx-4 flex justify-between">
	<h1>Start Bootstrap</h1>
	<ul class="flex list-none space-x-8">
		<li>
			<a href="/" class="text-blue-600">HOME</a>
		</li>
		<li>
			<a href="/about" class="text-blue-600">ABOUT</a>
		</li>
		<li>
			<a href="/services" class="text-blue-600">SERVICES</a>
		</li>
		<li>
			<a href="/contact" class="text-blue-600">CONTACT</a>
		</li>
	</ul>
</nav>
