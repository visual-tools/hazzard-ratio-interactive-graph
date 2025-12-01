<script>
	import '../app.pcss';
</script>

<!-- Mobile Warning Overlay -->
<div
	class="fixed inset-0 z-50 flex items-center justify-center bg-black/90 backdrop-blur-sm p-6 md:hidden"
>
	<div class="max-w-md text-center text-white">
		<h2 class="mb-4 text-2xl font-bold">Not Optimized for Mobile</h2>
		<p class="text-lg leading-relaxed">
			This visualization is not built for mobile phones. You can use your phone in horizontal mode
			if you want, but the graph is likely to be too small to read. For the best experience and to
			accurately read the data, please open the visualization on a desktop or laptop.
		</p>
	</div>
</div>

<div class="size-full min-w-svw min-h-svh pointer-events-none md:pointer-events-auto flex flex-col">
	<slot />
</div>
