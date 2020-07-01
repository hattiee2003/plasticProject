<script>
	export let segment

	let burger = false

	function toggleBurger() {
		burger = !burger
	}
</script>

<style>
	a {
		border-bottom: 1px solid white;
	}

 .is-active {
	 border-bottom: 1px solid black;
 }
</style>

<nav class="navbar">
  <div class="navbar-brand">

    <a class="navbar-item" class:is-active={segment === undefined} href=".">
			home
		</a>

		<!-- svelte-ignore a11y-missing-attribute -->
		<a role="button" class="navbar-burger burger" class:is-active={burger} on:click={toggleBurger} aria-label="menu" aria-expanded="false">
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
    </a>
  </div>
	<div class:is-active={burger} class="navbar-menu">
		<a class="navbar-item" class:is-active={segment === 'work'} href="work" on:click={()=> { burger = false; }}>
			my work
		</a>
		<a class="navbar-item" class:is-active={segment === 'products'} href="products" on:click={()=> { burger = false; }}>
			my products
		</a>
  </div>
</nav>