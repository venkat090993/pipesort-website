<style>

  .sectionB{
    margin-top: 200px;
    width:100%;

  
  }

h1 {
    font-weight: 700;
  }

.contain{
      width:100%;
      height: 100%;
        display: flex;
        flex-direction: row;
        justify-content: center;
        }

.item{
    position: relative;
    width:25rem;
    height: 20rem;
    padding: 10px;
    margin:10px;
   background-size: cover;
   transition:0.7s ease-in-out;
   background-repeat: no-repeat;
border: 1px solid rgb(204, 201, 201);

 }
 
 .item:hover{
    border: 1px solid rgb(204, 201, 201);
    box-shadow: 8px 8px 5px  rgb(204, 201, 201);
    opacity:0.9;
 }

 .item:after{
     position: absolute;
     top:90%;
     left: 0;
     bottom:0;
     right:0;
     content:attr(data-text);
     word-wrap: break-word;
     background-color:rgba(0,0,0,0.5);
     opacity: 0.9;
     color: rgb(221, 218, 218);
     padding: 0 10px;
     transition: 0.7s ease-in-out;
     overflow:hidden;
     white-space: pre-line;
 }
 
 .item:first-line{
     font-weight: bold;
     color: #fff;
     font-size:1.3em;
 }


 .item:hover:after{
     opacity:1;
     top:40%;
     padding:10px;
 }
 
    
h1{
text-align: center;
  }


    @media only screen and (max-width: 600px) {

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


  .item{
      width:90%;
      margin:auto;
      box-sizing: border-box;
      height: 500px;
      margin-bottom: 10px;
      
  }

}


   @media only screen and (max-width: 450px) {

       .sectionB{
        width:100%;

      }
  .contain {
    display: inline-block;
    }

h1{
text-align: center;
  }

.item{
      width:100%;
      margin:auto;
      background-size: 100%;
      box-sizing: border-box;
      height: 450px;
      margin-bottom: 10px;
      
  }

   .item:after{
     position: absolute;
     top:50%;
     left: 0;
     bottom:0;
     right:0;
     content:attr(data-text);
     word-wrap: break-word;
     background-color:#fd6378;
     opacity: 0.9;
     color: rgb(221, 218, 218);
     padding: 0 10px;
     transition: 0.7s ease-in-out;
     overflow:hidden;
     white-space: pre-line;
 }

}









</style>

<div class="sectionB">
<header>    <h1>Our Works</h1>
</header>
    <div class="contain">

        <div class="item" alt="AWS cloud"
        style="background-image:url('cloud-image.jp
        g')";
        data-text="AWS cloud
        High end consultation on moving a chunk or your entire workload to clould. We do a thorough analysis of your deployment architechture, provide you with insights on bottlenecks, migration risk and ideal cloud deployment architecture">
        </div>

          <div class="item" alt="web services"
        style="background-image:url('web-service.jpg')";
        data-text="Application development
        We help you in building highly intuitive and scalable web mobile and PWA apps with bleeding edge tech stacks.">
        </div>
        
           <div class="item" alt="consulting"
        style="background-image:url('training-service.jpg')";
        data-text="Consulting
        Providing advisory services in the development and delivery of digital and technology strategies">
        </div>

        </div>

            </div>
