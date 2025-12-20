<script lang="ts">
	import { page } from "$app/state";
</script>

<main class="min-h-screen bg-[#F7F7F8] flex items-center justify-center px-6">
	<div class="text-center">
		<h1 class="text-6xl font-medium text-[#110F28] mb-4">Error {page.status}</h1>
		<p class="text-xl text-gray-600 mb-8">{page.error?.message ?? "Something went wrong."}</p>
		<a href="/" class="bg-[#110F28] text-white text-sm font-medium px-8 py-3 rounded-full hover:bg-opacity-90 transition-opacity inline-block">Go back home</a>
	</div>
</main>
