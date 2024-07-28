<script>
	import '../app.css';
	import Navbar from '../components/Navegation/Navbar/index.svelte';
	import Footer from '../components/Navegation/Footer/index.svelte';
</script>

<Navbar />
<div class="min-h-screen">
	<slot />
</div>
<Footer />
