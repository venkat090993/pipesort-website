<script>
import OurWork from './ourWork.svelte';
import TechWeUse from './techWeUse.svelte';
import ContactForm from "./contactform.svelte";
import OurServices from './OurServices.svelte';
</script>

<style>

.header-text{
font-size: 3rem;
}
.header-text-2{
font-size: 1.5rem;
}

  .home-container {
    display: flex;
    flex: 1;
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
    padding-left:20px;
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
    position: relative;
    top:10px;
    right:10px;
  }

.wave{
position: absolute;
 background:#fd6378;
top:370px;
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
      width:100vh;
      margin:auto;
    }

    .home-copy {
      flex: 0;
      padding-bottom: 2em;
      padding-right: 2em;
      text-align: center;
    }

.wave{
position: absolute;
 display: none;
  }
  
  }

   @media only screen and (max-width: 450px) {
    .home-container {
            width:100%;
           margin: auto;
           padding-bottom:0;
           margin-bottom:0;
    }


   
.wave{
 display: none;
  }
  
  }
</style>

<svelte:head>
  <title>Pipesort Technologies</title>
</svelte:head>

<div class="home-container">
  <div class="home-copy">
<h1                                             data-aos="fade-zoom-in"
                                                data-aos-duration="2000"
                                                data-aos-easing="ease-in-out"
                                                data-aos-once="false"
                                                data-aos-anchor-placement="top-center" >We are a small team of <span class="seven">7</span></h1>  
  <p>Experienced <a href="/">Reactjs</a> developers rooting for <a href="/">Sveltejs</a>.
  </div>
  <figure>
    <img alt='Home page image' src='Homepage.svg' data-aos="zoom-in-left"
                                                data-aos-delay="50"
                                                data-aos-duration="1200"
                                                data-aos-easing="ease-in-out"
                                                data-aos-anchor-placement="top-center"

  >
  </figure>

</div>
<div class="wave"></div>

<OurWork />

<OurServices />

<TechWeUse />

<ContactForm />
