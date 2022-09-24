<script>
	import Header from "../components/header.svelte";
  import '../styles/global.css'
</script>

<svelte:head>
  <title>Svelte Kit Pokedex</title>
</svelte:head>

<Header />
<main class="pt-0 pb-8 px-8 max-w-6xl mx-auto">
  <slot></slot>
</main>
