<script>
    import MyComponent from './MyComponent.svelte';
</script>

<main>
    <h1>Aplikasi Svelte</h1>
    <MyComponent />
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

	h2 {
       color: teal;
   }

   	p {
       font-style: italic;
   }
</style>