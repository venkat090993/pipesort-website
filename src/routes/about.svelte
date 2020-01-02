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

    height:500px;
    width:100%;

    
    }




</style>


<div class="lg:container lg:flex lg:flex-col lg:justify-center lg:align-middle lg:w-10/12 lg:z-20 md:container md:flex md:flex-col md:justify-center md:align-middle md:w-11/12 md:z-20 sm: container sm: flex sm: flex-col sm: justify-center sm: align-middle sm: w-full sm: z-20">
<!-- outerdiv -->
<div>
<!-- container text div -->
<div class="lg:w-8/12 lg:m-auto md:w-8/12 md:m-auto sm: w-11/12 sm: m-auto">
<h1 
 class="lg:text-5xl lg:py-10 lg:text-center lg:block md:block md:text-5xl md:py-10 md:text-center sm: hidden">Web Design & Development</h1>
<h1 
class="sm: text-3xl sm: font-bold sm: py-10 sm: text-center lg:hidden md:hidden sm: block">Web Design</h1>
<p 
class="lg:text-2xl lg:text-center md:text-2xl md:text-center sm: text-xl sm: text-center" style="font-family:sans serif">We build websites optimized for what matters most — performance, sales, and happy customers that will return.</p>
</div>
<!-- closing text div -->

<!--main container-->
<div class="lg:container lg:flex lg:flex-col lg:mt-10 md:container md:flex md:flex-col md:mt-10 sm: container sm: flex sm: flex-col sm: mt-10 ">
<div class="lg:flex lg:flex-row lg:w-full md:flex md:flex-col md: w-full sm: flex-col  sm: w-full">
<!--left column-->
<div class="lg:flex lg:flex-col lg:w-1/2 md:flex md:flex-col md:w-full sm: flex sm: flex-col sm: w-full">

{#each itemList as item}

<div data-aos="zoom-in"
     data-aos-easing="ease-in-sine"
data-aos-ancor="bottom-top"
data-aos-duration="800" class=" lg:flex lg:flex-row lg:w-full lg:my-2 md:flex md:flex-row md:w-full md:py-2 shadow-md md:m-auto sm: m-auto  sm: flex sm: flex-row sm: w-5/6 sm: py-2 sm: my-2" >

<div class="lg:1/12 lg:bg-white-300 md:w-2/6 md:my-2 md:py-2 md:px-2 sm: w-1/5 sm: mt-8 ">
<img loading="lazy" class="lg:w-3/5 lg:h-1/2 md:w-1/2 m-auto align-middle sm: w-full sm: px-2" src={item.logo} alt="logo" />
</div>

<div class=" lg:w-11/12 lg:px-2 md:w-5/6 sm: w-full sm: py-5 sm: pr-5">
<h1 class="lg:text-2xl lg:py-5 md:text-2xl sm: text-xl sm: py-5 ">{item.title}</h1>
<p class="lg:text-xl md:text-xl sm: text-base" style="font-family:sans serif">{item.content}</p>
{#if item.tech != null}


{#each item.tech as tech}

<div class="lg:inline-block lg:my-1 lg:my-1 md:inline-block md:my-1 md:my-1 sm: inline-block sm: my-0">
<p class="lg:text-base lg:px-1 lg:p-1 lg:bg-blue-200 lg:m-1 md:text-base md:px-1 md:p-1 md:bg-blue-200 md:m-1 sm: text-xs sm: px-1 sm: p-1 sm: bg-blue-200 sm: m-1">{tech}</p>
</div>

{/each}
{/if}
</div>
</div>
{/each}
</div>

<!--right column-->

<div class=" lg:flex lg:flex-col lg:w-1/2 lg:row right sm: w-10/12 sm: m-auto">
<div class="flex flex-col w-full align-middle justify-center sm: w-10/12 sm: h-1/2 sm: m-auto">
<img loading="lazy" src="./lap.png" alt="bannerImage" class="lg:w-full lg:h-full lg:mt-20 md:w-full md:h-screen z-10" />
</div>

</div>
</div>
<!--closing main container-->
</div>
<!--Outer div-->

<!-- container text div -->
<div class="lg:w-8/12 lg:m-auto md:w-8/12 md:m-auto sm: w-11/12 sm: m-auto">
<h1 class="lg:text-5xl lg:py-10 lg:text-center lg:block md:block md:text-5xl md:py-10 md:text-center sm: hidden">Mobile App Design & Development</h1>
<h1  class="sm: text-3xl sm: font-bold sm: py-10 sm: text-center lg:hidden md:hidden sm: block">Mobile Design</h1>
<p class="lg:text-2xl lg:text-center md:text-2xl md:text-center sm: text-xl sm: text-center" style="font-family:sans serif">We design and build apps you can be proud of, while focusing on your goals for creating engaging user experiences.</p>
</div>
<!-- closing text div -->

<!--main container-->
<div  class="lg:container lg:flex lg:flex-col lg:mt-10 md:container md:flex md:flex-col md:mt-10 sm: container sm: flex sm: flex-col sm: mt-10 ">
<div class="lg:flex lg:flex-row-reverse lg:flex-row lg:w-full md:flex md:flex-col md: w-full sm: flex-col  sm: w-full">
<!--left column-->
<div class="z-20 lg:flex lg:flex-col lg:w-1/2 md:flex md:flex-col md:w-full sm: flex sm: flex-col sm: w-full">

{#each mobileItemList as item}

<div data-aos="zoom-out"
     data-aos-easing="ease-in-sine"
data-aos-ancor="bottom-top"
data-aos-duration="800" class=" lg:flex lg:flex-row lg:w-full lg:my-2 md:flex md:flex-row md:w-full md:py-2 shadow-md md:m-auto sm: m-auto  sm: flex sm: flex-row sm: w-5/6 sm: my-2 sm: py-2" >

<div class="z-20 lg:1/12 lg:bg-white-300 md:w-2/6 md:my-2 md:py-2 md:px-2 sm: w-1/5 sm: mt-8 ">
<img loading="lazy" class="lg:w-3/5 lg:h-1/2 md:w-1/2 md:w-1/2 md:h-1/2 m-auto align-middle sm: w-full sm: px-2" src={item.logo} alt="logo" />
</div>

<div class=" lg:w-11/12 lg:px-2 md:w-5/6 sm: w-full sm: py-5 sm: pr-5">
<h1 class="lg:text-2xl lg:py-5 md:text-2xl sm: text-xl sm: py-5 ">{item.title}</h1>
<p class="lg:text-xl md:text-xl sm: text-base" style="font-family:sans serif">{item.content}</p>
{#if item.tech != null}


{#each item.tech as tech}

<div class="lg:inline-block lg:my-1 lg:my-1 md:inline-block md:my-1 md:my-1 sm: inline-block sm: my-0">
<p class="lg:text-base lg:px-1 lg:p-1 lg:bg-blue-200 lg:m-1 md:text-base md:px-1 md:p-1 md:bg-blue-200 md:m-1 sm: text-xs sm: px-1 sm: p-1 sm: bg-blue-200 sm: m-1">{tech}</p>
</div>

{/each}
{/if}
</div>
</div>
{/each}
</div>

<!--right column-->

<div class=" lg:flex lg:flex-col lg:w-1/2 md:mt-10 md:m-auto  lg:row right sm: w-10/12 sm: m-auto">
<div class="lg:flex lg:flex-col lg:w-full lg:h-full lg:align-middle lg:justify-center md:flex md:flex-col md:align-middle md:w-full md:m-auto md:justify-center md:resposive-image md:align-middle sm: w-10/12 sm: m-auto">
<img  loading="lazy" src="./pho.png" alt="bannerImage" class="lg:w-4/5 lg:h-full lg:m-auto md:w-3/6 md:h-1/2 md:ml-40 lg:mt-16 sm: ml-0 z-10 " />
</div>

</div>
</div>
<!--closing main container-->
</div>
<!--Outer div-->

</div>
</div>

