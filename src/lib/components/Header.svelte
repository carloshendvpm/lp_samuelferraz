<script>
  import src from '$lib/images/samuelimg.png'
  import Links from './Links.svelte';
</script>
<header>
	<div class="flex justify-center flex-col items-center">
		<img {src} alt="" class="rounded-full w-24 mb-4">
		<h1 class="text-zinc-300 text-xl font-bold mb-1.5">Samuel Ferraz</h1>
		<p class="text-white w-80 mb-3 text-sm md:text-lg md:w-1/2 font-medium text-zinc-300 text-center">"O terno de inverno precisa ser costurado no <br>verão!"</p>
    <Links/>
	</div>
</header>