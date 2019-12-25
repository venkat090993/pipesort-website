<script>
  import Logo from './Logo.svelte'
  import Nav from './Nav.svelte'
  

  export let segment
</script>

<style>
  header {
    display: flex;
    margin: 0 auto;
    max-width: 1400px;
    padding: 2em;
    width: 100%;
  }

  .logo{
  display:block;
  padding-left:5rem;
  padding-top:10px;
  }

  .para{
 
  display:block;
  padding-left:1px;
  padding-top:28px;
  }

   @media screen and (max-width:450px){

       .logo{
            display: none;
            }
   }


</style>

<header class="flex flex-row justify-between">
<div class="logo"><Logo />
</div>

<!-- <p class="text-2xl para">.com</p> -->
<Nav {segment} />
</header>
