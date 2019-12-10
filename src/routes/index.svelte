<script>
import OurWork from './ourWork.svelte';
import TechWeUse from './techWeUse.svelte';
import ContactForm from "./contactform.svelte";
</script>

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
    height: 100vh;
    padding-bottom:20px; 
    padding:10px;
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

.wave{
position: absolute;
 background:#fd6378;
top:350px;
height: 143px;
width:100%;
background-image: url("/wave.png");
background-size: cover;
background-repeat: no-repeat;
transform: rotateX(180deg)
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
      width:calc(100vh);
    }

    .home-copy {
      flex: 0;
      padding-bottom: 2em;
      padding-right: 2em;
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

<div class="wave"></div>

<OurWork />

<TechWeUse />

<ContactForm />
