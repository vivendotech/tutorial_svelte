<script>
	import Componente from './Componente.svelte';
	
	export let name;
</script>

<style>
	h1 {
		color: purple;
	}
</style>

<h1>Hello {name}!</h1>


<Componente />
