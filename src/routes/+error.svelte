<script lang="ts">
	import { page } from "$app/state";
</script>

<main class="min-h-screen flex items-center justify-center bg-white px-4">
	<div class="text-center max-w-md">
		<div class="text-6xl mb-6">🐾</div>
		<h1 class="text-4xl font-serif font-bold mb-4">Oops! Error {page.status}</h1>
		<p class="text-gray-600 mb-8">{page.error?.message ?? "Something went wrong. Don't worry, your pet's song is safe!"}</p>
		<a href="/" class="inline-flex items-center justify-center px-6 py-3 rounded-full font-medium bg-dark text-white hover:bg-gray-800 transition-colors">
			Go Back Home &rarr;
		</a>
	</div>
</main>
