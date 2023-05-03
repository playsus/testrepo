<script>
import '../styles/main.css';
import Header from '../components/header/Header.svelte';
import Footer from '../components/footer/Footer.svelte';
import {} from '$lib/sentry'
</script>
<div class="app"><noscript><div class="alert alert-warning" role="alert"><strong>Your browser does not support JavaScript.</strong></div></noscript><Header /><main><slot /></main><Footer /></div>