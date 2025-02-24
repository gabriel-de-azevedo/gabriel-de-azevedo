<header>
  <h1>Hi. I'm<br />Gabriel.</h1>
  <p>I'm an amateur Digital Writer and professional Web Developer!</p>
</header>
<br />
<main>
  <h2>Here are some of my most recent projects:</h2>
  <ul>
    <li>
      <a
        href="https://gabriel-de-azevedo.github.io/contact-form/"
        target="_blank"
      >
        <img
          src="screenshots/contact-form.png"
          alt="Contact Form Project"
        />
      </a>
    </li>
    <li>
      <a
        href="https://gabriel-de-azevedo.github.io/recipe-page-main/"
        target="_blank"
      >
        <img src="screenshots/recipe-page.png" alt="Recipe Page Project" />
      </a>
    </li>
    <li>
      <a
        href="https://gabriel-de-azevedo.github.io/blog-preview-card-main/"
        target="_blank"
      >
        <img
          src="screenshots/blog-preview-card.png"
          alt="Blog Preview Card Project"
        />
      </a>
    </li>
  </ul>
</main>
<style>
  * {
    box-sizing: border-box;
  }
  body {
    max-width: 50rem;
    margin: 0 auto;
    display: grid;
    place-items: center;
    padding: 2em;
    gap: 2em;
    background: #fdfcdc;
    font-family: "Courier New", Courier, monospace;
    font-size: 1.5rem;
  }
  img {
    max-width: 100%;
    height: auto;
    display: block;
  }
  ul,
  li {
    padding: 0;
    list-style: none;
  }
  h2 {
    font-size: 1.25em;
  }
  ul {
    display: flex;
    flex-wrap: wrap;
    gap: 1em;
  }
  li img {
    max-height: 5em;
    border-radius: 0.25em;
    border: solid black 1px;
    box-shadow: 0.25em 0.25em black;
    transition-duration: 0.25s;
  }
  li img:hover {
    transform: rotate(5deg);
  }
</style>
