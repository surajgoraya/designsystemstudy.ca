<script>
	import { MetaTags } from 'svelte-meta-tags'; // Import the MetaTags component.

	/**
	 * The title of the page.
	 * @type {String}
	 */
	export let Title;
</script>

<MetaTags
	title={`Design System Study - ${Title}`}
	description="At what point do design systems become viable for organizations to 
    implement? What does the future of design systems look like? To answer these questions this
    study at the University of Guelph will set out to interview those who build, maintain, or use design systems across a variety of 
    organization sizes."
	canonical="https://designsystemstudy.ca/"
	openGraph={{
		url: 'https://designsystemstudy.ca/',
		title: `Design System Study - ${Title}`,
		description:
			'At what point do design systems become viable for organizations to implement? What does the future of design systems look like? To answer these questions this study at the University of Guelph will set out to interview those who build, maintain, or use design systems across a variety of organization sizes.',
		images: [
			{
				url: 'https://designsystemstudy.ca/ogp/ogp1.png',
				width: 1920,
				height: 1080,
				alt: 'A black and white image displaying the text "design system study." on the bottom left, in white and the text "University of Guelph" on the top right.'
			}
		],
		siteName: 'Design System Study - University of Guelph'
	}}
	keywords={[
		'design system',
		'design system study canada',
		'design systems study',
		'school of computer science',
		'university of guelph',
		'david flatla',
		'suraj goraya',
		'design research',
		'design systems research',
		'ui',
		'ux'
	]}
/>
<main class="container" id="content" tabindex="-1">
	<slot />
</main>
