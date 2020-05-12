<style lang="scss" scoped>
  footer {
    nav {
      padding: 3rem var(--basePadding);
      * {
        display: inline-block;
      }
      li {
        margin: 0 2rem;
      }
    }
  }
  .copyright {
    display: block;
    position: fixed;
    bottom: 0;
    left: 0;
    width: 100%;
    text-align: center;
    margin: 0;
    padding: 0 2rem;
    background: #0078cd;
    width: 100%;
  }

  @media (max-width: 880px) {
    footer {
      nav,
      ul,
      li {
        display: block;
      }
    }
  }
</style>

<footer>
  <nav>
    <p class="light-blue-text">}(</p>
    <ul>
      <li>
        <a href=".">home,</a>
      </li>
      <li>
        <a href="about">about,</a>
      </li>
      <li>
        <a rel="prefetch" href="portfolio">portfolio,</a>
      </li>
      <li>
        <a href="contact">contact</a>
      </li>
    </ul>
    <p class="light-blue-text">)</p>
  </nav>

</footer>
<p class="copyright">&copy; {new Date().getFullYear()} Pure Func LLC</p>
