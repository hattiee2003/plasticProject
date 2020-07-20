<script>
  export let segment;
</script>

<style>
  a {
    color: white;
  }

  .is-active {
    color: #fca311 !important;
  }

  nav {
    background-color: #14213d;
  }
</style>

<nav class="navbar" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">
    <a href=".">
      <img src="logo.png" alt="logo" />
    </a>
  </div>

  <div class="navbar-menu">
    <a class="navbar-item" class:is-active={segment === undefined} href=".">
      home
    </a>
    <a class="navbar-item" class:is-active={segment === 'work'} href="work">
      my work
    </a>
    <a class="navbar-item" class:is-active={segment === 'products'} href="products">
      my products
    </a>
  </div>
</nav>
