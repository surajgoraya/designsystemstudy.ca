<script>
  /**
   * @type {String} The title of the Alert.
   */
  export let title;
  /**
   * @type {String} The description of the Alert.
   */
  export let description;
</script>

<div role="alert" class="notice">
  <p class="notice__title"><i class="bi bi-info-square-fill"></i>&nbsp;&nbsp;{title}</p>
  <p class="notice__description">
    {description}
  </p>
</div>

<style>
  .notice {
    margin: -1.5rem 0 3rem 0;
    padding: 1.5rem 2rem;
    border-color: hsl(354, 67%, 56%);
    border-top: 0;
    border-style: dotted;
    border-spacing: 1rem;
  }
  .notice__title {
    background-color: hsl(354, 67%, 56%);
    color: #f7f7f7;
    margin: -2.3rem -2.3rem 1rem -2.3rem;
    padding: 2.5rem 2.3rem 1.5rem 2.3rem;
    font-weight: 800;
    font-size: 2rem;
  }
  .notice__description {
    font-weight: 300;
    font-size: 1.5rem;
    margin: 0;
  }
</style>
