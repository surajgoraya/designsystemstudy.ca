<!-- 
  @component 
  
  The Footer component is used to display a standardized footer, 
  featuring a copyright statement and the University of Guelph identifier.

  **NOTE: This element should be used on all pages.**
 -->

<hr />
<footer class="dimmed">
  &copy; 2023 Goraya & Flatla
  <img
    class="dimmed"
    src="/UofG_Identifier_stacked_blk_rgb.png"
    alt="The logo of the University of Guelph. In a serif font it displays the words 'University' at the top and 'of Guelph' just below it. The logo is surrounded by straight lines stacked on the top of the logo and on the bottom."
  />
</footer>

<style>
  footer {
    display: flex;
    align-items: center;
    justify-content: space-between;
  }

  footer > img {
    margin: 1rem 000;
    height: 40px;
    /* aspect-ratio: 16 / 9; */
  }

  .dimmed {
    opacity: 0.8;
  }
</style>
