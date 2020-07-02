<script>
	export let segment
</script>

<style>
	a {
		border-bottom: 1px solid white;
		color: white;
	}

 .is-active {
	 border-bottom: 1px solid black;
	 color: #FCA311 !important;
 }

 nav{
	 background-color: #14213D;
 }

</style>

<nav class="navbar" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">
	<a href=".">
		<img src="logo.png" alt="logo">
	</a>
</div>

	<div class="navbar-menu">
		<a class="navbar-item" class:is-active={segment === undefined} href=".">
			home
		</a>
		<a class="navbar-item" class:is-active={segment === 'work'} href="work" >
			my work
		</a>
		<a class="navbar-item" class:is-active={segment === 'products'} href="products">
			my products
		</a>
  </div>
</nav>