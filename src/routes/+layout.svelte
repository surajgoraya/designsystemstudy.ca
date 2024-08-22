<script>
  import Footer from '$lib/components/Footer.svelte';
  import Nav from '$lib/components/Nav.svelte';
  import Notice from '$lib/components/Notice.svelte';
  import SkipToMain from '$lib/components/SkipToMain.svelte';
</script>

<SkipToMain />
<Notice
  title={'Heads up!'}
  description={'The Design System Study at the University of Guelph has concluded. Thank you all those who reached out! Information regarding findings from the research conducted will be published soon~'}
/>
<Nav />
<slot />
<Footer />
