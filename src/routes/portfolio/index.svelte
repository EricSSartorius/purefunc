<!-- <script context="module">
  export function preload({ params, query }) {
    return this.fetch(`portfolio.json`)
      .then(r => r.json())
      .then(projects => {
        return { projects };
      });
  }
</script> -->

<!-- <script>
  export let projects;
</script> -->

<!-- <style lang="scss">
  ul {
    margin: 0 0 1em 0;
    line-height: 1.5;
  }
</style> -->

<svelte:head>
  <title>Portfolio</title>
</svelte:head>

<h1>Recent Projects</h1>

<p>Coming Soon</p>

<!-- <ul>
  {#each projects as project}
    <li>
      <a class="green-text" rel="prefetch" href="portfolio/{project.slug}">{project.title}</a>
    </li>
  {/each}
</ul> -->
