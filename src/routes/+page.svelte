<script lang="ts">
	import BlogCard from '$lib/Components/Cards/BlogCard.svelte';
</script>

<div class="grid grid-cols-1 gap-4 lg:grid-cols-3 lg:gap-8">
	{#each new Array(9) as _}
		<div class="min-h-32 rounded-lg bg-gray-200">
			<BlogCard />
		</div>
	{/each}
</div>
