<script lang="ts">
	import { m } from '$lib/paraglide/messages.js';
</script>

<div class="min-h-screen bg-background p-4 sm:p-8">
	<div class="mb-8 text-center">
		<h1 class="mb-2 text-2xl font-bold sm:text-3xl">{m['pages.home.hello_world']()}</h1>
		<p class="text-lg">Tailwind Theme Colors</p>
	</div>

	<div class="mx-auto max-w-6xl space-y-8">
		<!-- Core Colors -->
		<section>
			<h2 class="mb-4 text-xl font-semibold">Core Colors</h2>
			<div class="grid grid-cols-1 gap-4 sm:grid-cols-2 lg:grid-cols-4">
				<div class="rounded-lg bg-page p-4 text-white">
					<div class="font-semibold">page</div>
					<div class="text-sm opacity-90">#020617</div>
				</div>
				<div class="rounded-lg bg-background p-4 text-neutral-900">
					<div class="font-semibold">background</div>
					<div class="text-sm opacity-70">#fdf9f4</div>
				</div>
				<div class="rounded-lg bg-surface p-4 text-neutral-900">
					<div class="font-semibold">surface</div>
					<div class="text-sm opacity-70">#f4e6d8</div>
				</div>
				<div class="rounded-lg bg-muted p-4 text-neutral-900">
					<div class="font-semibold">muted</div>
					<div class="text-sm opacity-70">#e6e0d8</div>
				</div>
			</div>
		</section>

		<!-- Brand Colors -->
		<section>
			<h2 class="mb-4 text-xl font-semibold">Brand Colors</h2>
			<div class="grid grid-cols-1 gap-4 sm:grid-cols-2 lg:grid-cols-3">
				<div class="rounded-lg bg-primary p-4 text-neutral-900">
					<div class="font-semibold">primary</div>
					<div class="text-sm opacity-70">#c5d6cc</div>
				</div>
				<div class="rounded-lg bg-primary-soft p-4 text-neutral-900">
					<div class="font-semibold">primary-soft</div>
					<div class="text-sm opacity-70">#afc7df</div>
				</div>
				<div class="rounded-lg bg-secondary p-4 text-neutral-900">
					<div class="font-semibold">secondary</div>
					<div class="text-sm opacity-70">#afc7df</div>
				</div>
			</div>
		</section>

		<!-- Accent Colors -->
		<section>
			<h2 class="mb-4 text-xl font-semibold">Accent Colors</h2>
			<div class="grid grid-cols-1 gap-4 sm:grid-cols-2 lg:grid-cols-3">
				<div class="rounded-lg bg-accent p-4 text-neutral-900">
					<div class="font-semibold">accent</div>
					<div class="text-sm opacity-70">#f3c7c9</div>
				</div>
				<div class="rounded-lg bg-accent-strong p-4 text-white">
					<div class="font-semibold">accent-strong</div>
					<div class="text-sm opacity-90">#88a6a6</div>
				</div>
				<div class="rounded-lg bg-accent-soft p-4 text-neutral-900">
					<div class="font-semibold">accent-soft</div>
					<div class="text-sm opacity-70">#e3a8a9</div>
				</div>
			</div>
		</section>

		<!-- Semantic Colors -->
		<section>
			<h2 class="mb-4 text-xl font-semibold">Semantic Colors</h2>
			<div class="grid grid-cols-1 gap-4 sm:grid-cols-2">
				<div class="rounded-lg bg-warning p-4 text-neutral-900">
					<div class="font-semibold">warning</div>
					<div class="text-sm opacity-70">#d9b65d</div>
				</div>
				<div class="rounded-lg bg-info p-4 text-neutral-900">
					<div class="font-semibold">info</div>
					<div class="text-sm opacity-70">#d5c4e3</div>
				</div>
			</div>
		</section>

		<!-- Neutral Scale -->
		<section>
			<h2 class="mb-4 text-xl font-semibold">Neutral Scale</h2>
			<div class="grid grid-cols-2 gap-4 sm:grid-cols-5 lg:grid-cols-10">
				<div class="rounded-lg bg-neutral-50 p-3 text-neutral-900">
					<div class="text-xs font-semibold">50</div>
					<div class="text-xs opacity-70">#fdf9f4</div>
				</div>
				<div class="rounded-lg bg-neutral-100 p-3 text-neutral-900">
					<div class="text-xs font-semibold">100</div>
					<div class="text-xs opacity-70">#f4e6d8</div>
				</div>
				<div class="rounded-lg bg-neutral-200 p-3 text-neutral-900">
					<div class="text-xs font-semibold">200</div>
					<div class="text-xs opacity-70">#e6e0d8</div>
				</div>
				<div class="rounded-lg bg-neutral-300 p-3 text-neutral-900">
					<div class="text-xs font-semibold">300</div>
					<div class="text-xs opacity-70">#d5cec5</div>
				</div>
				<div class="rounded-lg bg-neutral-400 p-3 text-neutral-900">
					<div class="text-xs font-semibold">400</div>
					<div class="text-xs opacity-70">#b8aca1</div>
				</div>
				<div class="rounded-lg bg-neutral-500 p-3 text-white">
					<div class="text-xs font-semibold">500</div>
					<div class="text-xs opacity-90">#9b8c7f</div>
				</div>
				<div class="rounded-lg bg-neutral-600 p-3 text-white">
					<div class="text-xs font-semibold">600</div>
					<div class="text-xs opacity-90">#7d6f63</div>
				</div>
				<div class="rounded-lg bg-neutral-700 p-3 text-white">
					<div class="text-xs font-semibold">700</div>
					<div class="text-xs opacity-90">#5f5449</div>
				</div>
				<div class="rounded-lg bg-neutral-800 p-3 text-white">
					<div class="text-xs font-semibold">800</div>
					<div class="text-xs opacity-90">#41382f</div>
				</div>
				<div class="rounded-lg bg-neutral-900 p-3 text-white">
					<div class="text-xs font-semibold">900</div>
					<div class="text-xs opacity-90">#261f1b</div>
				</div>
			</div>
		</section>

		<!-- Primary Scale -->
		<section>
			<h2 class="mb-4 text-xl font-semibold">Primary Scale</h2>
			<div class="grid grid-cols-2 gap-4 sm:grid-cols-5 lg:grid-cols-10">
				<div class="rounded-lg bg-primary-50 p-3 text-neutral-900">
					<div class="text-xs font-semibold">50</div>
					<div class="text-xs opacity-70">#f6f9f7</div>
				</div>
				<div class="rounded-lg bg-primary-100 p-3 text-neutral-900">
					<div class="text-xs font-semibold">100</div>
					<div class="text-xs opacity-70">#eef3f0</div>
				</div>
				<div class="rounded-lg bg-primary-200 p-3 text-neutral-900">
					<div class="text-xs font-semibold">200</div>
					<div class="text-xs opacity-70">#e5ede8</div>
				</div>
				<div class="rounded-lg bg-primary-300 p-3 text-neutral-900">
					<div class="text-xs font-semibold">300</div>
					<div class="text-xs opacity-70">#dce6e0</div>
				</div>
				<div class="rounded-lg bg-primary-400 p-3 text-neutral-900">
					<div class="text-xs font-semibold">400</div>
					<div class="text-xs opacity-70">#d4e0d9</div>
				</div>
				<div class="rounded-lg bg-primary-500 p-3 text-neutral-900">
					<div class="text-xs font-semibold">500</div>
					<div class="text-xs opacity-70">#c5d6cc</div>
				</div>
				<div class="rounded-lg bg-primary-600 p-3 text-white">
					<div class="text-xs font-semibold">600</div>
					<div class="text-xs opacity-90">#a7b6ad</div>
				</div>
				<div class="rounded-lg bg-primary-700 p-3 text-white">
					<div class="text-xs font-semibold">700</div>
					<div class="text-xs opacity-90">#8a968f</div>
				</div>
				<div class="rounded-lg bg-primary-800 p-3 text-white">
					<div class="text-xs font-semibold">800</div>
					<div class="text-xs opacity-90">#626b66</div>
				</div>
				<div class="rounded-lg bg-primary-900 p-3 text-white">
					<div class="text-xs font-semibold">900</div>
					<div class="text-xs opacity-90">#3b403d</div>
				</div>
			</div>
		</section>
	</div>
</div>
