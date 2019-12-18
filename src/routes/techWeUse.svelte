<style>
.contain{
  display: flex;
  width:90%;
  margin:auto;
  
  }

  .slide-content{
    width:50%;
    height: 30%;
    margin:10px;

  }

  h1{
    text-align: center; }

.totalDiv{
  padding:50px;
}

@media only screen and (max-width: 600px){

 .contain{
margin:0;
width:100%;  
  }

  h1{
    width:100%;
    font-size: 30px;
  }

  .totalDiv{
   width:100%;
   display: flex;
   justify-content: center;
   flex-direction: column;
  }
}


@media only screen and (max-width: 450px){


 .contain{
width:100%;
padding:30px;  
  } 
  .totalDiv{
   width:100%;
  }  

}

 

</style>
<div class="totalDiv">
<h1>Tech We Use</h1>
<div class="contain">
    <Carousel class="carousel" loop autoplay={3000}>
      <img src="/react.png" class="slide-content" alt="react" loading="lazy" />
      <img src="/amazon.png" class="slide-content" alt="amazon" loading="lazy"  />
      <img src="/gatsby.png" class="slide-content" alt="gatsby" loading="lazy"   />
      <img src="/nodejs.png" class="slide-content"  alt="nodejs" loading="lazy"  />
      <img src="/graphql.png" class="slide-content"alt="react"  loading="lazy" />
    </Carousel>
</div>
</div>



<script>
	import Carousel from '@beyonk/svelte-carousel'
	import { ChevronLeftIcon, ChevronRightIcon } from 'svelte-feather-icons'
</script>