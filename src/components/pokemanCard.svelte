<script>
	import { fade } from 'svelte/transition';
	export let valueOfPokemon;
</script>

<div
	class="p-6 bg-gray-100 text-gray-800 text-center rounded-md shadow-sm hover:shadow-lg flex flex-col items-center"
>
	<img class="h-30 w-30" src={valueOfPokemon.image} alt={valueOfPokemon.name} />
	<h2 class="text-2xl uppercase">{valueOfPokemon.id} . {valueOfPokemon.name}</h2>
</div>
