<script lang="ts">
	import type { PageData } from './$types';

	export let data: PageData;

	$: ({ posts } = data);
</script>

<h1>Posts</h1>

<p>Showing {data.posts.length} posts.</p>

{#if data.posts.length > 0}
	<ul>
		{#each posts as { slug, title }, i}
			<li><a href="/posts/{slug}">{title}</a></li>
		{/each}
	</ul>
{/if}
