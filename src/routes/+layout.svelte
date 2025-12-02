<script lang="ts">
	import { page } from '$app/stores';
	import favicon from '$lib/assets/favicon.svg';
	import '../app.css';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

<nav class="sticky top-0 z-50 w-full border-b border-muted bg-background">
	<div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
		<div class="flex h-16 items-center justify-between">
			<a
				href="/"
				class="text-lg font-semibold text-neutral-900 transition-colors hover:text-primary-700 sm:text-xl"
			>
				ApoPhoto
			</a>

			<div class="flex items-center gap-4 sm:gap-6">
				<a
					href="/"
					class="text-sm text-neutral-700 transition-colors hover:text-primary-700 sm:text-base {$page
						.url.pathname === '/'
						? 'font-medium text-primary-700'
						: ''}"
				>
					Home
				</a>
				<a
					href="/theme"
					class="text-sm text-neutral-700 transition-colors hover:text-primary-700 sm:text-base {$page
						.url.pathname === '/theme'
						? 'font-medium text-primary-700'
						: ''}"
				>
					Theme
				</a>
			</div>
		</div>
	</div>
</nav>

<main>
	{@render children()}
</main>
