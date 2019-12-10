<script>
  import Carousel from "@beyonk/svelte-carousel";
  import { ChevronLeftIcon, ChevronRightIcon } from "svelte-feather-icons";
</script>

<style>
  h1 {
    text-align: center;
  }
  .divcontainer {
    display: flex;
    flex-direction: row;
    width: 100%;
    height: 60vh;
    margin: 0;
  }

  .image{
    height: 300px;
    width:100%;
    margin:0;
    padding:0;
 }

  .item {
    height: 70vh;
    width: 800px;
    border: 1px solid black;
    padding: 10px;
    margin: 10px;
    border-radius: 10px;
    box-shadow: 0;
    transition: box-shadow 0.5s;
    position: relative;
    display: flex;
    flex-direction: column;
  }

  .innerItem {
    height: 500px;
    width: 100%;
    background-color: red;
  }

  .item:hover {
    box-shadow: 5px 5px grey;
  }

  .figure {
    float: right;
    margin: -3em -7em 2em 2em;
    max-width: 400px;
  }

  figure img {
    border-radius: 8px;
  }

  @media (max-width: 1020px) {
    figure {
      float: none;
      margin: 0 auto 2em;
    }
  }
</style>

<svelte:head>
  <title>About</title>
</svelte:head>

<div>
  <h1>We build</h1>

  <div class="divcontainer">
  <form class="forms">
  <input type="text" />
  </form>

  </div>


</div>
