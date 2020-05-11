<script>
  export let segment;
  const home = () => {};
</script>

<style lang="scss">
  header {
    padding: 2rem var(--basePadding);
  }
  * {
    display: inline-block;
  }
  ul {
    display: flex;
    justify-content: space-between;
    li {
      margin: 0 2rem;
      font-size: var(--largeFontSize);
      &:hover {
        // [aria-current]::after {
        //   background-color: var(--orange);
        //   transition: all 0.3s;
        // }
      }
    }
  }

  [aria-current] {
    position: relative;
  }
  // [aria-current]::after {
  //   position: absolute;
  //   content: "";
  //   width: 100%;
  //   height: 1px;
  //   background-color: var(--red);
  //   display: block;
  //   bottom: 5px;
  // }
</style>

<header>
  <span class="purple-text">const</span>
  <h6 class="blue-text">{segment === undefined ? 'home' : segment}</h6>
  <span class="light-blue-text">= (</span>

  <nav>
    <ul>
      <li>
        <a aria-current={segment === undefined ? 'page' : undefined} href=".">
          home,
        </a>
      </li>
      <li>
        <a aria-current={segment === 'about' ? 'page' : undefined} href="about">
          about,
        </a>
      </li>
      <li>
        <a
          aria-current={segment === 'contact' ? 'page' : undefined}
          href="contact">
          contact,
        </a>
      </li>
      <li>
        <a
          rel="prefetch"
          aria-current={segment === 'portfolio' ? 'page' : undefined}
          href="portfolio">
          portfolio
        </a>
      </li>

    </ul>
  </nav>
  <span class="light-blue-text">)</span>
  <span class="purple-text">=></span>
  <span class="light-blue-text">&#123;</span>
</header>
