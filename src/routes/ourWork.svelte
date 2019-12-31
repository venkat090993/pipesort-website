<style>

  .sectionB{
    width:100%;
    margin-bottom: 5rem;
  }

    h1 {
    font-family: "montserrat";
  }

  p {
        font-family: "montserrat";
  }

  .contain{
      width:100%;
      height: 100%;
        display: flex;
        flex-direction: row;
        justify-content: center;
  }

  .sectionB .contain .item{
    width:25rem;
    height: auto;
    padding: 10px;
    margin:10px;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
         border: 1px solid rgb(204, 201, 201);
          box-shadow: 2px 2px 2px  rgb(204, 201, 201);

       
  }

  .sectionB .contain .item:hover{
      
          transition: 0.5s ease-in;
          border: 1px solid rgb(204, 201, 201);
          box-shadow: 6px 6px 6px  rgb(204, 201, 201);

  }
  

      .sectionB .contain .item:hover .button{
      color: white;
      border: 0.5px solid black ;
      transition: 0.5s ease-in;
      background: #fd6378;
    }



  .imageSection{
    height: 50%;
    width:100%;
    margin:auto;
  }


.contentSection{
    height: 50%;
    width:100%;
        margin:auto;
    background-color: #ffff;
    font-size: 11px;
    }

    .contentSection .content{
      padding:5px;

    }

    .button{
      width:100px;
      padding:5px;
      border: 0.5px solid black;
      color: #fd6378;
      background-color: aliceblue;
    }

    .logoImages{
        width:30px;
        height: 30px;
        padding:2px;
        margin:5px;
    }
    
h1{
text-align: center;
  }

    .logo{
        display: flex;
        flex-direction: row;
        justify-content: flex-start;
        margin-bottom: 10px;
    }

    @media only screen and (max-width: 728px) {

       h1{
    width:100%;
    font-size: 30px;
  }


    .sectionB{
    width:100%;
  }
  .contain {
    display: inline-block;
    }


  .sectionB .contain .item{
      width:90%;
      margin:auto;
      box-sizing: border-box;
      height: 500px;      
  }

}


   @media only screen and (max-width: 450px) {

       .image{
           width:100px;
       }

       .sectionB{
        width:90%;
        margin: auto;

      }
  .contain {
    display: inline-block;
    }

h1{
text-align: center;
  }

  .sectionB .contain .item{
      width:100%;
      margin:auto;
      box-sizing: border-box;
      height: auto;
      margin-bottom: 10px;
      
  }

        .logoImages{
        width:40px;
        height: 40px;
        padding:2px;
        margin:5px;
    }
}









</style>

<div class="sectionB sm: pt-10">
<header>    <h1 class="text-6xl font-extrabold mb-5 sm: pb-2" data-aos="fade-zoom-in"
     data-aos-easing="ease-in-back"
     data-aos-duration="1000"
     data-aos-once="true"
     data-aos-offset="0">Our Works</h1>
</header>
    <div class="contain">

        <div data-aos="zoom-in"
        data-aos-delay="300"
     data-aos-duration="1000" class="item ">
            <div class="imageSection bg-blue-100 sm: h-auto">
            <img src="https://s3.amazonaws.com/dermio-admin/images/dermio-logo-lg.png" class="lg:h-1/2 w-full p-4 lg:mt-16 xl:mt-12 sm: my-20 " alt="dermio" />
            </div>
            <div class="contentSection">
                <div class="content">
                    <h4 class="text-2xl pb-5 pt-1 font-bold"> DERMIO</h4>
                    <p class="pb-2 text-xl" style="font-family:sans serif">Chat-bot based HIPAA compliant online consulting app</p>
                    <br />
                    <div class="logo">
                    <img loading="lazy" class="logoImages" src="/chatbot.png" alt="" />
                    <img loading="lazy" class="logoImages" src="/react.png" alt="" />
                    <img loading="lazy" class="logoImages" src="/nodejs.png" alt="" />
                    <img loading="lazy" class="logoImages" src="/amazon.png" alt="" />
                    </div>
                    <!-- <button class="button">Read More...</button> -->
                </div>
            </div>
        </div>
        <div data-aos="zoom-in" 
         data-aos-delay="300"
     data-aos-duration="1500"
     class="item">
            <div class="imageSection bg-black shadow-xl sm: h-auto">
            <img src="ct-full.svg" class="h-full w-full p-4 mt-0 bg-black shadow-xl sm: mt-0" alt="Arokiya" />
            </div>
            <div class="contentSection">
                <div class="content">
                    <h4 class="text-2xl pb-5 pt-1 font-bold"> AROKIYA</h4>
                    <p class="pb-2 text-xl" style="font-family:sans serif">E-commerce solutions for an online grocery shop</p>
                    <br />
                    <div class="logo">
                    <img loading="lazy" class="logoImages" src="/react.png" alt="" />
                    <img loading="lazy" class="logoImages" src="/gatsby.png" alt="" />
                    <img loading="lazy" class="logoImages" src="/nodejs.png" alt="" />
                    <img loading="lazy" class="logoImages" src="/amazon.png" alt="" />
                    </div>
                    <!-- <button class="button">Read More...</button> -->
                </div>
            </div>
        </div>

        <div data-aos="zoom-in"
         data-aos-delay="300"
     data-aos-duration="1500"
      class="item">
            <div class="imageSection sm: h-auto">
            <img loading="lazy" src="RHACC-logo-dark.svg" class="h-full w-full p-4 m-0 bg-gray-200 " alt="RHACC" />
            </div>
            <div class="contentSection">
                <div class="content">
                    <h4 class="text-2xl font-bold pb-5 pt-1"> RHACC</h4>
                    <p class="pb-2 text-xl" style="font-family:sans serif">Edu-tech project for an university to handle their courses and management</p>
                    <br />
                    <div class="logo">
                    <img loading="lazy" class="logoImages" src="/react.png" alt="" />
                    <img loading="lazy" class="logoImages" src="/gatsby.png" alt="" />
                    <img loading="lazy" class="logoImages" src="/nodejs.png" alt="" />
                    <img loading="lazy" class="logoImages" src="/amazon.png" alt="" />
                    </div>
                    <!-- <button class="button">Read More...</button> -->

                </div>
            </div>
        </div>
    </div>
</div>