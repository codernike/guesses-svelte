<script>
	import Footer from './libs/footer.svelte';
	import Navbar from './libs/navbar.svelte';


</script>

<header>
<Navbar/>
</header>
<div class="d-flex flex-column min-vh-100">
    <main class="flex-fill">
<main>
<slot></slot>
</main></main></div>

<footer>
    <Footer/>
</footer>
