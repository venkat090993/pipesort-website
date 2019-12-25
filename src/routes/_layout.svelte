<script>
  import Header from '../components/Header.svelte';
  import AOS from 'aos';
import 'aos/dist/aos.css';
  export let segment;
import {onMount} from "svelte";

onMount( ()=>{

    AOS.init( 
      {
  // Global settings:
  disable: false, // accepts following values: 'phone', 'tablet', 'mobile', boolean, expression or function
  startEvent: 'DOMContentLoaded', // name of the event dispatched on the document, that AOS should initialize on
  initClassName: 'aos-init', // class applied after initialization
  animatedClassName: 'aos-animate', // class applied on animation
  useClassNames: false, // if true, will add content of `data-aos` as classes on scroll
  disableMutationObserver: false, // disables automatic mutations' detections (advanced)
  debounceDelay: 50, // the delay on debounce used while resizing window (advanced)
  throttleDelay: 99, // the delay on throttle used while scrolling the page (advanced)
  

  // Settings that can be overridden on per-element basis, by `data-aos-*` attributes:
  offset: 120, // offset (in px) from the original trigger point
  delay: 0, // values from 0 to 3000, with step 50ms
  duration: 400, // values from 0 to 3000, with step 50ms
  easing: 'ease', // default easing for AOS animations
  once: false, // whether animation should happen only once - while scrolling down
  mirror: false, // whether elements should animate out while scrolling past them
  anchorPlacement: 'top-bottom', // defines which position of the element regarding to window should trigger the animation

}
  );

})
  
</script>

<style>
  .layout {
    display: flex;
    flex-direction: column;
    min-height: 100%;
    min-height: 100vh;
    width:100%;
  }

  main {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    position: relative;
    margin:auto;
    max-width: 1400px;
    background-color: white;
    /* padding: 1em 2em; */
    box-sizing: border-box;
    width: 100%;
    display: flex;
    flex-direction: column;
    font-family: "montserrat"; }

  footer {
    color: #AAA;
    font-size: 1em;
    font-family: montserrat, sans-serif;
    margin: 1em auto;
    max-width: 1400px;
    padding: 1em 2em;
    text-align: center;
    width: 100%;
  }
</style>

<div class="layout">
  <Header {segment}/>

  <main>
    <slot></slot>
  </main>

  <footer class="flex flex-row">
  <div class="w-1/2 h-64 bg-black flex flex-col align-middle justify-center">
  <p><a href="/">70.com</a></p>
  <p>copyright@2019 70.com</p></div>

  <div class="w-1/2 h-64 bg-black flex flex-col align-middle justify-center">
  <p><a href="/contactform">Contact us</a></p>
  </div>
    </footer>
</div>
