<!-- 
	@component
	
	This component is used for compliance with WCAG SC 2.4.1 (see: https://www.w3.org/TR/UNDERSTANDING-WCAG20/navigation-mechanisms-skip.html),
	it displays a "skip to main content" link at the top of the page when tabbed / highlighted into focus (otherwise it stays hidden).

	*NOTE This component should be placed at the top of every page, before the navigation element*
	
 -->
<a class="skip_link" href="#content">Skip To Main Content</a>

<style>
	.skip_link {
		left: -999px;
		top: 0;
		position: absolute;
		overflow: hidden;
		z-index: -999;
	}
	.skip_link:focus,
	.skip_link:active {
		color: #fff;
		background-color: #000;
		left: 0;
		top: 0;
		width: 100%;
		padding: 1rem;
		height: auto;
		overflow: auto;
		z-index: 999;
	}
</style>
