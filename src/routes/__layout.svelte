<header>
  <a class="logo-link" href="/">
    <h1 class="logo">Vamp</h1>
  </a>
  <nav class="nav">
    <a class="nav-item" href="/learn">Learn</a>
    <a class="nav-item" href="/docs">Docs</a>
    <a class="nav-item" href="/play">Play</a>
  </nav>
</header>

<slot />

<style>
  :global(html, body) {
    margin: 0;
    padding: 0;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial,
      sans-serif, "Apple Color Emoji", "Segoe UI Emoji";
  }

  header {
    background: #000000;
    color: #ffffff;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 16px 32px;
  }

  .logo-link {
    color: inherit;
    text-decoration: none;
  }

  .logo {
    font-family: "DM Sans";
    margin: 0;
    font-weight: 700;
    font-size: 2rem;
    letter-spacing: 0.02em;
    line-height: 1;
    text-transform: uppercase;
  }

  .nav {
    display: flex;
  }

  .nav-item {
    color: inherit;
  }

  .nav-item:not(:last-child) {
    margin-right: 32px;
  }

  .nav-item:hover {
    text-decoration: none;
  }
</style>
