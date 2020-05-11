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
    .copyright {
      display: block;
      text-align: center;
      margin: 0;
      padding: 0 2rem;
      background: #0078cd;
      width: 100%;
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
        <a href="contact">contact</a>
      </li>
    </ul>
    <p class="light-blue-text">)</p>
  </nav>

  <p class="copyright">&copy; {new Date().getFullYear()} Pure Func LLC</p>
</footer>
