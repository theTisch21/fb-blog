<script context="module" lang="ts">
	export const prerender = true;
</script>

<script lang="ts">
	
</script>

<svelte:head>
	<title>BLOG</title>
	<meta name="description" content="BLOG" />
</svelte:head>

<section>
	<h1>
		<div class="welcome">
			<picture>
				<source srcset="svelte-welcome.webp" type="image/webp" />
				<img src="svelte-welcome.png" alt="Welcome" />
			</picture>
		</div>

		TO MY BLOG LOL<br>
	</h1>
	<a href="/blog"><button class="leFancy">GO TO BLOG</button></a>

</section>

<style>
	.leFancy {
		width: 300px;
		height: 100px;
		border-radius: 30px;
		font-size: 40px;
		font-weight: bolder;
		color: var(--text-color);
		background-color: var(--accent-color);
		transition: all 1s;
	}
	.leFancy:hover {
		background-color: var(--text-color);
		color: var(--accent-color);
	}
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 1;
	}

	h1 {
		width: 100%;
	}

	.welcome {
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 495 / 2048) 0;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	}
</style>
