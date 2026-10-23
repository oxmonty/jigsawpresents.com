<script lang="ts">
	const title = 'Jigsaw Presents';
	const description =
		'Video essays on the stories, sounds, and scenes shaping culture. Coming 2027.';
	const youtube = 'https://www.youtube.com/channel/UCx8iHEGQMyeInLgPQ81-EJA?sub_confirmation=1';
</script>

<svelte:head>
	<title>{title}</title>
	<meta name="description" content={description} />
	<meta property="og:title" content={title} />
	<meta property="og:description" content={description} />
</svelte:head>

<main
	class="flex min-h-dvh flex-col items-center justify-center bg-paper px-4 text-center font-sans text-ink"
>
	<h1 class="text-2xl font-medium tracking-tight">{title}</h1>
	<p class="mt-3 max-w-md leading-relaxed text-balance">{description}</p>
	<a
		href={youtube}
		target="_blank"
		rel="noopener noreferrer"
		class="mt-6 underline underline-offset-4 hover:no-underline"
	>
		YouTube<span aria-hidden="true">&#8599;</span>
	</a>
</main>
