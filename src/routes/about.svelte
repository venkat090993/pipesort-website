<script>

let itemList = [{title:"Optimized", content:"What good is a website if it doesn't bring you more customers and sales? We design and build websites optimized for conversions.", logo:"./settingscolor.svg"},
{title:"Responsive", content:"Look equally amazing on desktop, tablet, and mobile. Rest assure that we care to provide great experience on all platforms.", logo:"./laptopcolor.svg"},
{title:"Easy to Manage", content:"We integrate with various content management solutions (CMS) to make website management a breeze.", logo:"./levelscolors.svg"},
{title:"Technologies we use", content:"We use JavaScript based frameworks for server-side and client-side development. We use relational as well as NoSQL databases for faster processing of complex set of data.", logo:"./shieldcolor.svg", tech:["React js" , "Node.js", "Typescript", "Svelte", "AngularJS", "Gatsbyjs", "MEAN"]},
]

let mobileItemList = [{title:"Consultation", content:"We take care of product research, use cases, and competitor analysis to help you build a strong project foundation", logo:"./loupe.svg"},
{title:"UI Design & Interaction", content:"We design for a consistent look and feel and focus on specific micro-interactions between screens and UI elements.", logo:"./UI.svg"},
{title:"App Development", content:"We delop native iOS and Android apps as well as hybrid mobile apps depending on your needs, business goals, and target audience.", logo:"./app.svg"},
{title:"Technologies we use", content:"Experts in developing experiential applications using native as well as hybrid technologies for mobile, tablets and connected devices.", logo:"./ux-design.svg", tech:["React Native", "Flutter"]},
]

 
</script>

<style>

.image{
    height: 700px;
}

.imagephone{

    height:100vh;
    width: 100%;
    
    }

@media screen and (max-width: 768px){

    .image{
        margin-top: 10px;
    height: 400px;
}

.imagephone{
   margin-top: 10px;
   margin-left:10px;
   height:100%;
    width: 80%;
    
    }

@media screen and (max-width: 450px){

    .image{
    height: 300px;
}

.imagephone{

    height:200px;
    width: 250px;
    
    }
}


}

</style>


<div class="lg:container lg:flex lg:flex-col lg:justify-center lg:align-middle lg:w-full lg:z-20 md:container md:flex md:flex-col md:justify-center md:align-middle md:w-full md:z-20 sm: container sm: flex sm: flex-col sm: justify-center sm: align-middle sm: w-full sm: z-20">
<!-- outerdiv -->
<div>
<!-- container text div -->
<div class="lg:w-8/12 lg:m-auto md:w-8/12 md:m-auto sm: w-8/12 sm: m-auto">
<h1 class="lg:text-5xl lg:py-10 lg:text-center lg:block md:block md:text-5xl md:py-10 md:text-center sm: hidden">Web Design & Development</h1>
<h1 class="sm: text-3xl sm: font-bold sm: py-10 sm: text-center lg:hidden md:hidden sm: block">Web Design</h1>
<p class="lg:text-xl lg:text-center md:text-xl md:text-center sm: text-base sm: text-center">We build websites optimized for what matters most — performance, sales, and happy customers that will return.</p>
</div>
<!-- closing text div -->

<!--main container-->
<div class="lg:container lg:flex lg:flex-col lg:mt-10 md:container md:flex md:flex-col md:mt-10 sm: container sm: flex sm: flex-col sm: mt-10 ">
<div class="lg:flex lg:flex-row lg:w-full md:flex md:flex-col md: w-full sm: flex-col  sm: w-full">
<!--left column-->
<div class="lg:flex lg:flex-col lg:w-1/2 md:flex md:flex-col md:w-full sm: flex sm: flex-col sm: w-full">

{#each itemList as item}

<div class=" lg:flex lg:flex-row lg:w-full lg:my-2 md:flex md:flex-row md:w-full md:py-2 shadow-md md:m-auto sm: m-auto  sm: flex sm: flex-row sm: w-full sm: py-2" >

<div class="lg:1/12 lg:bg-white-300 md:w-2/6 md:my-2 md:py-2 md:px-2 sm: w-1/5 sm: mt-8 ">
<img class="lg:w-3/5 lg:h-1/2 md:w-1/2 m-auto align-middle sm: w-full sm: px-2" src={item.logo} alt="logo" />
</div>

<div class=" lg:w-11/12 lg:px-2 md:w-5/6 sm: w-full sm: py-5 sm: pr-5">
<h1 class="lg:text-xl lg:py-5 md:text-xl sm: text-xl sm: py-5 ">{item.title}</h1>
<p class="lg:text-base md:text-base sm: text-sm">{item.content}</p>
{#if item.tech != null}


{#each item.tech as tech}

<div class="inline-block my-2">
<p class="text-base  px-1 p-1 bg-blue-200 m-1">{tech}</p>
</div>

{/each}
{/if}
</div>
</div>
{/each}
</div>

<!--right column-->

<div class=" lg:flex lg:flex-col lg:w-1/2 lg:row right sm: w-10/12 sm: m-auto">
<div class="flex flex-col align-middle justify-center sm: w-10/12 sm: m-auto sm: b">
<img src="./pipesortimage.png" alt="bannerImage" class="image" />
</div>

</div>
</div>
<!--closing main container-->
</div>
<!--Outer div-->

<!-- container text div -->
<div class="lg:w-8/12 lg:m-auto md:w-8/12 md:m-auto sm: w-8/12 sm: m-auto">
<h1 class="lg:text-5xl lg:py-10 lg:text-center lg:block md:block md:text-5xl md:py-10 md:text-center sm: hidden">Mobile App Design & Development</h1>
<h1 class="sm: text-3xl sm: font-bold sm: py-10 sm: text-center lg:hidden md:hidden sm: block">Mobile Design</h1>
<p class="lg:text-xl lg:text-center md:text-xl md:text-center sm: text-base sm: text-center">We design and build apps you can be proud of, while focusing on your goals for creating engaging user experiences.</p>
</div>
<!-- closing text div -->

<!--main container-->
<div class="lg:container lg:flex lg:flex-col lg:mt-10 md:container md:flex md:flex-col md:mt-10 sm: container sm: flex sm: flex-col sm: mt-10 ">
<div class="lg:flex lg:flex-row-reverse lg:flex-row lg:w-full md:flex md:flex-col md: w-full sm: flex-col  sm: w-full">
<!--left column-->
<div class="lg:flex lg:flex-col lg:w-1/2 md:flex md:flex-col md:w-full sm: flex sm: flex-col sm: w-full">

{#each mobileItemList as item}

<div class=" lg:flex lg:flex-row lg:w-full lg:my-2 md:flex md:flex-row md:w-full md:py-2 shadow-md md:m-auto sm: m-auto  sm: flex sm: flex-row sm: w-full sm: py-2" >

<div class="lg:1/12 lg:bg-white-300 md:w-2/6 md:my-2 md:py-2 md:px-2 sm: w-1/5 sm: mt-8 ">
<img class="lg:w-3/5 lg:h-1/2 md:w-1/2 md:w-1/2 md:h-1/2 m-auto align-middle sm: w-full sm: px-2" src={item.logo} alt="logo" />
</div>

<div class=" lg:w-11/12 lg:px-2 md:w-5/6 sm: w-full sm: py-5 sm: pr-5">
<h1 class="lg:text-xl lg:py-5 md:text-xl sm: text-xl sm: py-5 ">{item.title}</h1>
<p class="lg:text-base md:text-base sm: text-sm">{item.content}</p>
{#if item.tech != null}


{#each item.tech as tech}

<div class="inline-block my-2">
<p class="text-base  px-1 p-1 bg-blue-200 m-1">{tech}</p>
</div>

{/each}
{/if}
</div>
</div>
{/each}
</div>

<!--right column-->

<div class=" lg:flex lg:flex-col lg:w-1/2 lg:row right sm: w-10/12 sm: m-auto">
<div class="flex flex-col align-middle justify-center sm: w-10/12 sm: m-auto">
<img src="./desktop.svg" alt="bannerImage" class="imagephone" />
</div>

</div>
</div>
<!--closing main container-->
</div>
<!--Outer div-->

</div>
</div>

