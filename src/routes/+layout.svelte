<script>
	import '../app.css';

	let { children } = $props();
</script>

<header class="flex w-full flex-row flex-nowrap gap-4">
	<div class="logo">✍️</div>
	<nav class="flex flex-1 list-none flex-row gap-4">
		<li>Posts</li>
		<li>About</li>
		<li>Contact</li>
	</nav>
	<ul class="socials flex flex-row">
		<li>😊</li>
		<li>👍</li>
		<li>😒</li>
	</ul>
</header>
<main class="w-full p-4 md:p-10">
	{@render children()}
</main>
