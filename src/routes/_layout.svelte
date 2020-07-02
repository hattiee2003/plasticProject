<script>
	import Nav from './_components/Nav.svelte'

	export let segment
</script>

<style>
footer {
    background-color:#14213D;
    color: white;
    padding: 10px;  
}
header{
    background-color:#14213D;
    color: white;
    padding: 10px;
    font-size: 35px;
}
p {
    display: block;
}
</style>

<header>
    <h1>UnitC</h1>
</header>

<Nav {segment}/>

<main class="section">
	<slot></slot>
</main>

<footer>
    <p style="font-size: 20px;">Contact:</p><p>Name: Roger Dennison</p><p>Email: rodger@unitc.co.nz</p>   <p>Mobile: 021 039 1969</p><p>Home Phone: 03 337 5635</p><br>
    <p>&copy Harriet Eglinton and Julia Wakeman 2020</p>
</footer>