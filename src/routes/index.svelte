<style>
  img {
    display: block;
    margin-left: auto;
    margin-right: auto;
    height: 200px;
    width: 100%;
    border-radius: 5px;
  }

  img:hover {
    box-shadow: 0 12px 16px 0 rgba(0, 0, 0, 0.384),
      0 17px 50px 0 rgba(0, 0, 0, 0.384);
    transition-duration: 0.4s;
  }

  .column {
    display: inline-block;
    width: 33.33%;
    padding: 5px;
  }

  .row{
    text-align: center;
  }

  .row::after {
    content: "";
    clear: both;
    display: table;
  }

  h2 {
    text-align: center;
    padding-top: 20px;
  }
</style>

<div class="row">
  <div class="column">
    <a href="/work">
      <img src="actionPlastics.png" alt="link to work page" />
      <h2 class="subtitle">My Work</h2>
    </a>
  </div>

  <div class="column">
    <a href="/products">
      <img src="curtain.jpg" alt="link to products page" />
      <h2 class="subtitle">My Products</h2>
    </a>
  </div>
</div>
