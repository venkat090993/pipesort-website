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
  }

   @media screen and (max-width:450px){

       .logo{
            display: none;
            }
   }


</style>

<header>
<div class="logo">  <Logo />
</div>
  <Nav {segment} />
</header>
