<script lang="ts">
	import "smelte/src/tailwind.css" ;
	import Login from './components/login/Login.svelte';
</script>

<main>
	<h1>Login Page</h1>
	<Login/>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>