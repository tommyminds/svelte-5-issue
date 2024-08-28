<script>
	import { someExport } from '$lib/ComponentB.svelte';

	function onClick() {
		console.log(someExport.foo);
	}
</script>

<button onclick={onClick}>Click me</button>
