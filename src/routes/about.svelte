<style lang="scss">
  ul {
    font-size: var(--largeFontSize);
    margin: 2rem;
    li {
      margin: 1rem;
    }
  }
  .close-bracket {
    font-size: var(--heading-four);
    margin: var(--margins);
  }
</style>

<svelte:head>
  <title>About</title>
</svelte:head>

<h1>About Us</h1>

<p>
  Pure Func is a web development agency commited to making blazing fast, modern
  websites. We specialize in static e-commerce websites for small companies but
  also offer other development solutions.
</p>

<h2>The Founder</h2>
<p>
  Eric Sartorius is a digital nomad that enjoys coding from all around the
  globe. He has been developing websites since 2014 and has had the pleasure to
  work with clients from all corners of the earth.
</p>
<h4 class="blue-text">
  Eric's Contact
  <span class="light-blue-text">= &#123;</span>
</h4>

<ul>
  <li>
    E-mail:
    <a class="green-text" href="mailto:eric@purefunc.dev">eric@purefunc.dev</a>
  </li>
  <li>
    Homepage:
    <a
      class="green-text"
      href="https://ericsartorius.com"
      target="_blank"
      rel="noopener noreferrer">
      ericsartorius.com
    </a>
  </li>
</ul>
<span class="light-blue-text close-bracket">}</span>
