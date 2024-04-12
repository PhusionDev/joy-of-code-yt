<h1>Home</h1>

<!-- <script lang="ts">
	import type { Post } from '@prisma/client';

	async function getPosts() {
		const response = await fetch('api/posts');
		const posts: Post[] = await response.json();

		return posts;
	}
</script>

<h1>Posts</h1>

{#await getPosts()}
	<p>Loading...</p>
{:then posts}
	<p>Showing {posts.length} posts.</p>
	<ul>
		{#each posts as post, index}
			<li><a href="/posts/{post.slug}">{post.title}</a></li>
		{/each}
	</ul>
{:catch error}
	<p>{error.message}</p>
{/await} -->
