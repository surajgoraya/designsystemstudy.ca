<script>
	export const trailingSlash = 'always';
	export const prerender = true;
	
	import Footer from '$lib/components/Footer.svelte';
	import Nav from '$lib/components/Nav.svelte';
	import SkipToMain from '$lib/components/SkipToMain.svelte';

</script>

<SkipToMain/>
<Nav />
<slot />
<Footer />
