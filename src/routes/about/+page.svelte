<script>
  import Template from '$lib/components/Template.svelte';
</script>

<Template Title="About">
  <h1>About</h1>
  <section id="who">
    <h2>Who is Running This Study</h2>
    <p>
      This study is being run at the University of Guelph's School of Computer Science. The
      University of Guelph is one of Canada's top comprehensive and research-intensive universities.
      More information about the university can be found on it's website, linked here: <a
        href="https://www.uoguelph.ca/about/">University of Guelph | About the University</a
      >
    </p>
    <h3>The Researchers</h3>
    <div id="david-flatla">
      <div class="image_container">
        <img src="/researchers/david_flatla.jpg" alt="a front on of David Flatla" />
      </div>
      <p>
        <strong>David Flatla</strong> is an
        <a href="https://www.uoguelph.ca/computing/people/david-flatla"
          >Associate Professor at the University of Guelph</a
        >, he specializes in the field of Human-Computer Interaction, specifically the sub-domain of
        Accessibility. His research explores augmenting human perception to both overcome sensory
        impairments as well as to help people with typical abilities understand what it is like to
        have a sensory impairment.
      </p>
    </div>
    <div id="suraj-goraya">
      <div class="image_container">
        <img src="/researchers/suraj_goraya.jpg" alt="a 3/4ths side profile of Suraj" />
      </div>
      <p>
        <strong>Surajpratap Goraya</strong> is a MSc Candidate at the University of Guelph, his research
        specializes in the field of Human-Computer Interaction, specifically the sub-domain of User Experience
        and User Interfaces. His current research focuses on Design Systems.
      </p>
    </div>
  </section>
  <section id="contact">
    <h2>Questions, Contact & More Information</h2>
    <p>
      For any questions, or for more information regarding the study, please contact <a
        href="mailto:gorayas@uoguelph.ca">gorayas@uoguelph.ca</a
      >.
    </p>
  </section>
</Template>

<style>
  div {
    display: flex;
    gap: 2rem;
  }
  div > .image_container {
    margin-top: .5rem;
    align-self: flex-start;
    aspect-ratio: 1/1;
    height: 100px;
  }

  .image_container > img {
    object-position: top;
    object-fit: cover;
    min-width: 100%;
    min-height: 100%
  }
</style>
