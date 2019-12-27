<script>
  import Logo from './Logo.svelte'
  import Nav from './Nav.svelte'
  

  export let segment
</script>

<style>
  header {
    display: flex;
    margin: 0 auto;
    /* max-width: 1400px; */
    padding: 2em;
    width: 100%;
    /* background: red; */
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

  .nav{
      width:100%
  }

       @media screen and (max-width:768px){

       .logo{
            display: block;
              padding-left:2rem;
  padding-top:10px;
            }
   }

     @media screen and (max-width:560px){

              .logo{
            display: block;
              padding-left:1rem;
  padding-top:10px;
            }
   }

   @media screen and (max-width:450px){

       .nav{
           width:100%;
           margin: auto;
           margin-left: -5px;

       }

       .logo{
            display: none;
            }
   }

 



</style>

<header class="flex flex-row justify-between">
<div class="logo"><Logo />
</div>

<!-- <p class="text-2xl para">.com</p> -->
<div class="nav">
<Nav {segment} />
</div>
</header>
