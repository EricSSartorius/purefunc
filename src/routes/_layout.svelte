<script>
  import Nav from "../components/Nav.svelte";
  import Footer from "../components/Footer.svelte";

  export let segment;
</script>

<style lang="scss" global>
  @import "./styles/reset.scss";
  @import "./styles/classes.scss";
  @import "./styles/global.scss";
</style>

<Nav {segment} />

<main>
  <slot />
</main>

<Footer />
