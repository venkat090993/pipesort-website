<script>
import OurWork from './ourWork.svelte';
import TechWeUse from './techPage.svelte';
import ContactForm from "./contactform.svelte";
import About from "./about.svelte";
import Cloud from "./cloudInternal.svelte";

</script>

<style>

.hr{
    width:100%;
    height:2px;
    background-color: black;
}

.logo{
    visibility: visible;
}

.header-text{
font-size: 3rem;
}
.header-text-2{
font-size: 1.5rem;
}

  .home-container {
      position: relative;
      flex:1;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    align-items: center;
    height: 80vh;
    }

  /* .seven{
    color:#fd6378;
    font-size: 8rem;
    margin:0
  } */

.base{
    position: absolute;
    text-align: center;
    margin:auto;

}

.base h1{
    font-size: 6rem;
}

.para{
    position: absolute;
    text-align: center;
    margin:auto;
}


.inner-container{ 
display: flex;
flex-direction: column; 
width:100%;
height: 300px;
justify-content: center;
align-items: center;
margin-top:100px;
}

.base:first-child{
    opacity: 0;
    visibility: hidden; 
    animation: anim 4s linear 1;
    }
.base:nth-child(2){
    opacity: 0;
    visibility: hidden; 
    animation: anim 4s 4s linear 1;
}
.base:nth-child(3){
    opacity: 1;
    animation: anim1 4s 8s linear 1 both;
} 


@keyframes anim{
    0%, 30%{
        opacity: 0;
        bottom:43%;
visibility: hidden; 
    }
    40%,90%{
        bottom:50%;
        opacity: 1;
        visibility: visible
    }
      95%,100%{
        opacity: 0;
        bottom:50%;
visibility: hidden; 
    }
} 

@keyframes anim1{
    0%, 30%{
        opacity: 0;
        bottom:43%;
visibility: hidden; 
    }
    40%,60%{
        bottom:50%;
        opacity: 1;
        visibility: visible
    }
      70%,100%{
        opacity: 1;
        bottom:50%;
        visibility: visible;
    }



} 

.body-container{ 
    position: relative;
display: flex;
flex-direction: column; 
width:100%;
height: 500px;
justify-content: center;
align-items: center;
margin-top: -37rem;
}

.para:first-child{
    opacity: 0;
    visibility: hidden; 
     animation: bodyAnimation 4s linear 1; 
    }
.para:nth-child(2){
    opacity: 0;
    visibility: hidden; 
     animation: bodyAnimation 4s 4s linear 1; 
}
.para:nth-child(3){
    opacity: 1;
    visibility: hidden;
    animation: bodyAnimation3 4s 8s linear 1 both; 
} 


@keyframes bodyAnimation{
    0%, 30%{
        opacity: 0;
        top:45%;
visibility: hidden; 
    }
    40%,90%{
        top:50%;
        opacity: 1;
        visibility: visible
    }
      95%,100%{
        opacity: 0;
        top:50%;
visibility: hidden; 
    }
} 

@keyframes bodyAnimation3 {
0%, 30%{
        opacity: 0;
        top:45%;
visibility: hidden; 
    }
    40%,60%{
        top:50%;
        opacity: 1;
        visibility: visible
    }
      70%,100%{
        opacity: 1;
        top:50%;
        visibility: visible
    }


} 




 
  @media (max-width: 1024px) {
    .home-container {
      flex-direction: column;
      flex:1;
      text-align: center;
      /* width:100%; */
      margin:auto;
    }

.base h1{
    font-size: 3rem;
}


.para{
    position: absolute;
    text-align: center;
    margin:auto;
    word-wrap: break-word;
    width:100%;
}
.body-container{ 
    position: relative;
display: flex;
flex-direction: column; 
width:100%;
height: 400px;
justify-content: center;
align-items: center;
/* margin-top: -34rem; */
}



@keyframes anim{
    0%, 30%{
        opacity: 0;
        bottom:35%;
visibility: hidden; 
    }
    40%,90%{
        bottom:38%;
        opacity: 1;
        visibility: visible
    }
      95%,100%{
        opacity: 0;
        bottom:38%;
visibility: hidden; 
    }
} 

@keyframes anim1{
    0%, 30%{
        opacity: 0;
        bottom:35%;
visibility: hidden; 
    }
    40%,60%{
        bottom:38%;
        opacity: 1;
        visibility: visible
    }
      70%,100%{
        opacity: 1;
        bottom:38%;
        visibility: visible;
    }



} 

@keyframes bodyAnimation{
    0%, 30%{
        opacity: 0;
        top:50%;
visibility: hidden; 
    }
    40%,90%{
        top:60%;
        opacity: 1;
        visibility: visible
    }
      95%,100%{
        opacity: 0;
        top:60%;
visibility: hidden; 
    }
} 

@keyframes bodyAnimation3 {
0%, 30%{
        opacity: 0;
        top:50%;
visibility: hidden; 
    }
    40%,60%{
        top:60%;
        opacity: 1;
        visibility: visible
    }
      70%,100%{
        opacity: 1;
        top:60%;
        visibility: visible
    }


} 
  
  }

   @media only screen and (max-width: 450px) {
    .home-container {
            width:100%;
           margin: auto;
           padding-bottom:0;
           flex:1;
           margin-bottom:0;
    }

.inner-container{ 
display: flex;
flex-direction: column; 
width:100%;
height: 300px;
justify-content: center;
align-items: center;
}

.base h1{
    font-size: 3rem;
}

.para{
    position: absolute;
    text-align: center;
    margin:auto;
    word-wrap: break-word;
    width:100%;
    font-family:"neuton"
}

.logo{
    visibility: visible;
}
.body-container{ 
    position: relative;
display: flex;
flex-direction: column; 
width:100%;
height: 400px;
justify-content: center;
align-items: center;
/* margin-top: -34rem; */
}



@keyframes anim{
    0%, 30%{
        opacity: 0;
        bottom:30%;
visibility: hidden; 
    }
    40%,90%{
        bottom:35%;
        opacity: 1;
        visibility: visible
    }
      95%,100%{
        opacity: 0;
        bottom:35%;
visibility: hidden; 
    }
} 

@keyframes anim1{
    0%, 30%{
        opacity: 0;
        bottom:30%;
visibility: hidden; 
    }
    40%,60%{
        bottom:35%;
        opacity: 1;
        visibility: visible
    }
      70%,100%{
        opacity: 1;
        bottom:35%;
        visibility: visible;
    }



} 

@keyframes bodyAnimation{
    0%, 30%{
        opacity: 0;
        top:60%;
visibility: hidden; 
    }
    40%,90%{
        top:65%;
        opacity: 1;
        visibility: visible
    }
      95%,100%{
        opacity: 0;
        top:65%;
visibility: hidden; 
    }
} 

@keyframes bodyAnimation3 {
0%, 30%{
        opacity: 0;
        top:60%;
visibility: hidden; 
    }
    40%,60%{
        top:65%;
        opacity: 1;
        visibility: visible
    }
      70%,100%{
        opacity: 1;
        top:65%;
        visibility: visible
    }


} 

  
  }
</style>


<svelte:head>
  <title>Pipesort Technologies</title>
</svelte:head>

<div style="background: url('grey.png')" class=" shadow-xl flex flex-col justify-start items-center lg:w-full lg: pb-10 md:w-full sm: w-full sm: h-full">

<div class="home-container flex flex-col lg:-mb-20 justify-start items-center lg:w-full md:w-full md:-mb-20 md:mt-24 sm: w-full sm: h-full">

<div class="lg:w-20 lg:h-20 lg:bg-red-800 lg:-mt-10 lg:logo md:w-20 md:h-20  md:mt-20 md:bg-red-800 md:logo sm: w-20 sm: h-20 sm: bg-red-800 sm: logo sm: mt-16"><img src="702logo.svg" alt="logo" /></div>

<div class="w-1/2 flex flex-col justify-start h-1/2 items-center lg:-mt-12 md:-mt-20 sm: -mt-10 sm: h-1/2">

<p class="lg:text-center lg:w-full lg:text-5xl lg:mb-12 lg:font-extrabold md:text-3xl md:font-bold md:text-center md:w-64 sm: text-2xl sm: w-64  sm: mt-20 sm: text-2xl sm: font-bold">We're experts in</p>

<div class="inner-container sm: w-screen m-auto">

<div class="base lg:text-6xl font-bold sm: text-5xl " style="color:#F07041">
<h1>Design</h1>
</div>
 

<div class='base lg:text-6xl font-bold sm: text-5xl' style="color:#e52780">
<h1>Custom-app</h1> 
</div> 

<div class="base lg:text-6xl font-bold sm: text-5xl" style="color:#532d87">
<h1>Cloud</h1>
</div>



</div>

<div class="body-container flex flex-col ">

<div class="para">
<p class="text-2xl">Rich and exotic design that suits your brand</p>
</div>
 

<div class='para'>
<p class="text-2xl">Web and Mobile app tailor-made for your needs</p>
</div> 

<div class="para">
<p  class="text-2xl">Shifting data to cloud using AWS</p>
</div>

</div>
</div>
</div>

</div>
<!-- <hr class="hr"/> -->
<About />

<Cloud />

<OurWork />

<!-- <TechWeUse /> -->