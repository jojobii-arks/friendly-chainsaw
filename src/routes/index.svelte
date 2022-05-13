<script>
	import Header from '../components/Header.svelte';
	import { onMount } from 'svelte';
	let h2;

	onMount(() => {
		console.dir(h2);
	});
</script>

<Header />

<div class="prose text-center min-w-full">
	<h1>Heading 1</h1>
	<h2>Heading 2</h2>
	<h3>Heading 3</h3>
	<h4>Heading 4</h4>
	<p>A Paragraph</p>
	<button class="btn">Button</button>
</div>

<div class="flex items-center justify-center py-16">
	<div class="card bg-primary text-primary-content w-96">
		<div class="card-body text-center items-center">
			<h2 class="card-title">Card</h2>
			<p>Now this is epic.</p>
		</div>
	</div>
</div>

<div class="flex items-center justify-center py-16">
	<div class="card glass  w-96">
		<div class="card-body text-center items-center">
			<h2 class="card-title">Card</h2>
			<p>Now this is epic.</p>
		</div>
	</div>
</div>
