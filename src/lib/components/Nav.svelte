<!-- 
	@component

	This component is used to display a navigation bar at the top of every page.

  **NOTE: This element should be used on all pages.**
 -->
<nav>
  <div class="nav">
    <div class="brand">
      <img
        src="/temp_logo.png"
        alt="A logo for the Design System Study. It displays a black box with the words: 'design system study.' in all lower-case and bold inside of it. The words 'University of Guelph' are displayed on the left, flipped 90 degrees, outside of the box in black."
      />
      <!-- <div class="logo">
                <p>Design System Study</p>
            </div> -->
    </div>
    <ul class="navigation">
      <li><a href="/">home</a></li>
      <li><a href="/#how-do-i-participate">how do i participate?</a></li>
      <li><a href="/about">about</a></li>
    </ul>
  </div>
  <hr />
</nav>

<style>
  .nav {
    margin-top: 1rem;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }

  nav .brand {
    width: 10rem;
  }

  .navigation {
    list-style: none;
    display: flex;
    gap: 0.5rem;
    padding: 0px;
  }

  .navigation > li:not(:last-child)::after {
    content: ' · ';
  }

  @media screen and (max-width: 640px) {
    .nav {
      margin-top: 2rem;
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      justify-content: center;
    }

    nav .brand {
      width: 10rem;
    }
  }
</style>
