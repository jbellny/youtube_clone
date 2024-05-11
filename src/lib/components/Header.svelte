<script lang="ts">
	import SearchBar from './SearchBar.svelte';
</script>

<header
	class="sticky left-0 top-0 z-10 flex h-[64px] items-center justify-between bg-white px-4 py-2"
>
	<div class="flex items-center gap-4">
		<img
			src="/icons/burgerIcon.svg"
			class="cursor-pointer rounded-full p-3 hover:bg-gray-200"
			alt=""
		/>
		<img src="/icons/ytLogo.svg" alt="" />
	</div>
	<SearchBar />
	<div class="flex items-center gap-3">
		<img
			src="/icons/createIcon.svg"
			class="cursor-pointer rounded-full p-3 hover:bg-gray-200"
			alt=""
		/>
		<img
			src="/icons/noteIcon.svg"
			class="cursor-pointer rounded-full p-3 hover:bg-gray-200"
			alt=""
		/>
		<div class="flex h-12 w-12 items-center justify-center rounded-full hover:bg-gray-200">
			<img src="/avatar.png" class="h-8 w-8 cursor-pointer rounded-full hover:bg-gray-200" alt="" />
		</div>
	</div>
</header>
