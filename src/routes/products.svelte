<style>
  h1 {
    text-align: center;
  }

  a {
    text-decoration: none;
    color: black;
  }

img {
    display: block;
    margin-left: auto;
    margin-right: auto;
    height: 200px;
    border-radius: 5px;
  }

  img:hover{
    box-shadow: 0 12px 16px 0 rgba(0, 0, 0, 0.384),
      0 17px 50px 0 rgba(0, 0, 0, 0.384);
    transition-duration: 0.4s;
  }

  /* Three image containers (use 25% for four, and 50% for two, etc) */
.column {
  float: left;
  width: 33.33%;
  padding: 5px;
}

/* Clear floats after image containers */
.row::after {
  content: "";
  clear: both;
  display: table;
}
  
h2 {
  text-align: center;
  padding-top: 20px;
}

p{
  text-align: center;
}
</style>

<h1 class="title">My Products</h1>
<br />
<h2 class="subtitle">
  Here are some products I have made myself. To purchase, contact me using contacts below.
</h2>

<div class="row">
  <div class="column">
    <a href="/curtain">
    <img src="curtain.jpg" alt="m system curtain track">
    <h2 class="subtitle">M-System Curtain Track</h2>
    <p>$</p>
  </div>

  <div class="column">
    <a href="/shakle">
    <img src="dShakle.jpg" alt="D shakle">
    <h2 class="subtitle">D Shakle</h2>
    <p>$</p>
  </div>

  <div class="column">
    <a href="/milk">
    <img src="milk.jpg" alt="raw milk chilly bin">
    <h2 class="subtitle">Raw Milk Chilly Bin</h2>
    <p>$</p>
  </div>
</div>


