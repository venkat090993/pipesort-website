<style>

.header-text{
font-size: 3rem;
}
.header-text-2{
font-size: 1.5rem;
}

  .home-container {
    align-items: center;
    display: flex;
    flex: 1;
    justify-content: center;
    min-height: 400px;
  }

  .seven{
    color:#fd6378;
    font-size: 8rem;
    margin:0
  }

  .home-copy {
    flex: 1;
  }

  h1 {
    font-weight: 700;
  }

  p {
    font-size: 1.4em;
  }

  figure {
    margin: 0 1em;
    text-align: center;
  }

  figcaption {
    font-size: .8em;
    font-style: italic;
  }

  img {
    width: 100%;
    max-width: 400px;
  }

  @media (max-width: 1020px) {
    p {
      font-size: 1.2em;
    }

    img {
      max-width: 300px;
    }
  }

  @media (max-width: 800px) {
    .home-container {
      flex-direction: column;
      text-align: center;
    }

    .home-copy {
      flex: 0;
      padding-bottom: 2em;
      text-align: center;

    }

  }
</style>

<svelte:head>
  <title>Pipesort Technologies</title>
</svelte:head>

<div class="home-container">
  <div class="home-copy">
<h1>We are a small team of <span class="seven">7</span></h1>  
  <p>Experienced <a href="/">Reactjs</a> developers rooting for <a href="/">Sveltejs</a>.
  </div>
  <figure>
    <img alt='Person typing on laptop' src='undraw-illustration.svg'>
    <figcaption>Illustration thanks to <a href="https://undraw.co" target="_blank">Undraw</a></figcaption>
  </figure>
</div>
