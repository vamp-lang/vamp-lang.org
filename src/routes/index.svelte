<svelte:head>
  <title>Vamp</title>
</svelte:head>

<main>
  <div class="columns">
    <div class="column">
      <h2>A programming language focused on</h2>
    </div>
  </div>
  <div class="columns">
    <div class="column">
      <h3>Safety</h3>
      <p>
        Vamp is a purely functional programming language with strict typing.
        Vamp's type inference makes the use of explicit type hints optional in
        most cases. Assertion types provide strong guarantees about program
        correctness throughout the development process.
      </p>
    </div>
    <div class="column">
      <h3>Simplicity</h3>
      <p>
        Vamp has a minimalist syntax and small set of composable primitive types
        that are easy to learn. A high-level overview of the language fits
        nicely on <a href="/cheatsheet">a single page</a>. Once Vamp reaches the
        1.0 milestone, the core language will remain stable.
      </p>
    </div>
  </div>
  <div class="columns">
    <div class="column">
      <h3>Productivity</h3>
      <p>
        Vamp reduces decision fatigue by providing batteries-included tooling
        for package management, linting, autoformatting, as well as a <a
          href="/docs">comprehensive standard library</a
        >. A
        <a href="https://microsoft.github.io/language-server-protocol/"
          >Language Server Protocol (LSP)</a
        >
        implementation makes editor integration seamless.
      </p>
    </div>
    <div class="column">
      <h3>Portability</h3>
      <p>
        Vamp aims to eventually target native, WebAssembly, and JavaScript.
        Cross-platform code will be written with conditional imports and FFI to
        C-family, Rust, and JavaScript.
      </p>
    </div>
  </div>
</main>

<style>
  main {
    padding: 16px 0;
    margin: 0 auto;
    max-width: 1280px;
  }

  .columns {
    display: flex;
  }

  @media (max-width: 720px) {
    .columns {
      flex-direction: column;
    }
  }

  .column {
    padding: 16px 32px;
    flex: 1;
  }

  h2 {
    margin: 0 0 0.5em 0;
    font-size: 1.5rem;
    font-weight: 700;
    line-height: 1;
  }

  h3 {
    margin: 0 0 0.5em 0;
    font-size: 1.125rem;
    font-weight: 700;
    line-height: 1;
  }

  p {
    margin: 0;
    font-size: 1rem;
    line-height: 1.5;
    margin-bottom: 1em;
  }

  a {
    color: #15843e;
  }
</style>
