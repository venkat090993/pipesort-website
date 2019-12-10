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
    text-align: center;
    margin:20px;
line-height: 10rem  }

.totalDiv{
  padding:50px;
}

@media only screen and (max-width: 600px){

 .contain{
   margin-top:20px;
padding:20px;
width:100vh;  
  }
  

}

 

</style>
<div class="totalDiv">
<h1>Tech We Use</h1>
<div class="contain">
    <Carousel loop autoplay={3000}>
      <img src="/react.png" class="slide-content" />
      <img src="/amazon.png" class="slide-content" />
      <img src="/gatsby.png" class="slide-content" />
      <img src="/nodejs.png" class="slide-content" />
      <img src="/graphql.png" class="slide-content" />
    </Carousel>
</div>
</div>



<script>
	import Carousel from '@beyonk/svelte-carousel'
	import { ChevronLeftIcon, ChevronRightIcon } from 'svelte-feather-icons'
</script>