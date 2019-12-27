<script>
  export let segment;
</script>

<style>
  nav {
    align-items: flex-end;
    display: flex;
    flex: 1;
    font-family: montserrat, sans-serif;
    font-weight: 700;
    justify-content: flex-end;
    text-transform: uppercase;
    /* background: #fd6378;     */
  }

  a {
    color: inherit;
    text-decoration: none;
    padding: 10px 5px;
    display: block;
    position: relative;
    margin-left: 20px;
  }

  a:not(.selected) {
    opacity: 0.7;
  }

  a::before {
    content: '';
    position: absolute;
    transition: transform .3s ease;
    left: 0;
    bottom: 0;
    width: 100%;
    height: 2px;
    background: #AAA;
    transform: scaleX(0);
  }

  a:hover::before,
  .selected::before {
    transform: scaleX(1);
  }

  .selected::before {
    background: #fd6378;
    /* background:#24d0c5; */
  }



    @media screen and (max-width:370px){

         nav{
          width:100%;
          display: flex;
          flex-direction: row;
          justify-content: center;
          align-items: flex-end;
          margin:0 5px;
          box-sizing: border-box;
      }

          a {
    color: inherit;
    text-decoration: none;
    padding: 10px 5px;
    position: relative;
    font-size: 12px;
  }
    }

      @media screen and (max-width:425px){
       nav{
          width:100%;
          display: flex;
          flex-direction: row;
          justify-content:center;
          align-items: flex-end;
          margin:0 5px;
          box-sizing: border-box;

      }}
</style>

<nav>
  <a class='{segment === undefined ? "selected" : ""}' href='.'>home</a>
  <a rel=prefetch class='{segment === "cloud" ? "selected" : ""}' href='contactform'>contact</a>
    <a rel=prefetch class='{segment === "cloud" ? "selected" : ""}' href='about'>about
    </a>
  <a rel=prefetch class='{segment === "blog" ? "selected" : ""}' href='blog'>blog</a>
</nav>
