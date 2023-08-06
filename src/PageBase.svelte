<script lang="ts">
	import Menu from './components/Menu.svelte'
	import MenuItem from './components/MenuItem.svelte'
</script>

<Menu>
	<MenuItem url="/">Home</MenuItem>
	<MenuItem url="/about">About</MenuItem>
</Menu>

<main>
	<slot /></main>

