<script>
  import Template from '$lib/components/Template.svelte';
</script>

<Template Title={null}>
  <img
    class="heading"
    src="ds-unsplash.jpg"
    alt="A Mac computer displaying Figma. The Figma application on the screen is displaying a design system, there are various canvases showing words such as 'Components', 'Colours', 'etc...'. The computer is partially obstructed by out of focus green leafs from a plant "
  />
  <h1>Design System Study</h1>
  <div class="study-info">
    <b>STUDY INFORMATION</b>
    <p>
      <i class="bi bi-person-fill" aria-label="Authors: "></i> Surajpratap Goraya,
      <a href="https://scholar.google.ca/citations?user=pJjyC-AAAAAJ&hl=en&oi=ao"
        >Dr. David Flatla</a
      >,
    </p>
    <p>
      <i class="bi bi-mortarboard-fill" aria-label="University / Institution: "></i>
      <a href="https://www.uoguelph.ca/computing/">University of Guelph</a>, Ontario, Canada,
    </p>
    <p>
      <i class="bi bi-geo-fill" aria-label="Location: "></i>
      Conducted online only, via Microsoft Teams (fully remote).
    </p>
  </div>
  <section id="introduction">
    <p>
      This study is being conducted at the <a href="https://uoguelph.ca/about/"
        >University of Guelph's</a
      > <a href="https://socs.uoguelph.ca/">School of Computer Science (SoCS).</a>
      The primary focus of this study is to explore issues with the use, maintenance, and implementation
      of design systems within organizations, particularly with how these issues interact with team/organizational
      size.
    </p>
    <p />
    <p>
      Its secondary focus is on exploring what the future of design systems looks like. Have design
      systems achieved what they set out to do? Have they outstayed their welcome? We're interested
      in the thoughts design system practitioners have about where they see design systems now, and
      where they see them in the future.
    </p>
  </section>
  <section class="what-happens-during-the-study">
    <h2>What happens during the study?</h2>
    <p>
      We're inviting you to a one-on-one approximately 60-minute interview over the video
      conferencing software, Microsoft Teams. We will ask you around 12 open ended questions in this
      semi-structured interview. These questions will begin as general related to design systems, to
      gauge overall knowledge and definitions used within your organization. they will then
      transition to asking you about any challenges or issues you face within your organization when
      implementing, maintaining, and using design systems. We will then, finally move onto your
      personal thoughts on design systems, and where you think they're going.
    </p>
    <p>
      A flexible time will be set-up which works for both the interviewers and the interviewees. The
      interview questions will also be provided to you in the email confirming your date and time
    </p>
    <p>
      The audio and visual of the interview will be recorded using the interviewers laptop and the
      interviewer will also take notes during the interview, so we do not miss what you say. You
      will receive a monetary incentive for your time (see: Benefits & Incentives below).
    </p>
  </section>
  <section id="benefits-and-incentives">
    <h2>Benefits & Incentives</h2>
    <p>
      <strong>You will be provided an incentive of $20 Canadian Dollars (CAD)</strong>, for your
      participation in this study, which will be sent to you via e-Transfer, PayPal, or Amazon Gift
      Card (your choice). If you choose to withdraw, there will be no penalty and you will still be
      provided the full incentive ($20 CAD equivalent Amazon Gift Card, PayPal, or e-Transfer).
    </p>
    <p>
      it is unlikely that there will be any other direct benefits to you, however, by better
      understanding your experiences, researchers in this field may be able to better tailor their
      research.
    </p>
  </section>
  <section id="how-do-i-participate">
    <h2>How do I Participate?</h2>
    <p><b>We'd love to have you!</b>, thank you so much for expressing your interest!</p>
    <h3>Our Inclusion Criteria</h3>
    <p>
      This study is <b>open to anyone 18-years or older</b> who currently works on design systems as a
      designer or developer (or equivalent role). We're looking for participants from a wide variety
      of organization sizes (small, medium and large), as defined by <a
        href="https://ised-isde.canada.ca/site/sme-research-statistics/en/key-small-business-statistics/key-small-business-statistics-2022#sB"
      >
        Innovation, Science and Economic Development Canada</a
      >
      (Canada's Ministry of Industry).
      <br/>
      <br/>
      <b>This means we're looking for those working in the following sized organizations:</b>
    </p>
    <ul>
      <li><strong>Small:</strong> 1 to 99 paid employees.</li>
      <li><strong>Medium:</strong> 100 to 499 paid employees.</li>
      <li><strong>Large:</strong> 500 or more paid employees.</li>
    </ul>
    <!-- <h3>Contact</h3> -->
    <p class="study-info">
      <b>If you fit our criteria and would like to participate: </b> please email
      <a href="mailto:gorayas@uoguelph.ca">gorayas@uoguelph.ca</a> expressing your interest, we'd love
      to have you!
    </p>
    <p>
      Once you email, we will provide you with additional information, a consent form and the
      interview questions!
    </p>
  </section>
</Template>

<style>
  .heading {
    object-fit: cover;
    height: 20vh;
    width: 100%;
    aspect-ratio: 16/9;
    margin: 1rem 0 -2rem 0;
  }
  .study-info {
    border-style: dotted;
    border-spacing: 1rem;
    padding: 1rem;
    margin: 2rem 0 3rem 0;
  }

  .study-info > p {
    margin: 0.5rem 0 0 0;
  }
</style>
