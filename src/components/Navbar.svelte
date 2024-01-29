<script>
	import { DarkMode } from 'flowbite-svelte';
</script>

<nav
	class="flex justify-between items-center mb-4 pb-4 border-b border-gray-300 dark:border-gray-700"
>
	<a href="/">
		<div class="font-bold text-xl tracking-widest">
			LOOM<span class="text-sky-600 dark:text-sky-300">SOCIAL</span>
		</div>
	</a>

	<div class="flex items-center space-x-4">
		<span class="text-lg font-medium">
			<a href="/">Home</a>
		</span>
		<span class="text-lg font-medium">
			<a href="/blog">Blog</a>
		</span>

		<DarkMode size="lg" />
	</div>
</nav>
