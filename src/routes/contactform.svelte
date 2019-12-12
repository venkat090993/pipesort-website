<style>

.contact-us{
    width: 100%;
    padding:0;
    margin:0;
    background:linear-gradient(to right, #f84ab0,60%,  #cc2b5e);
    height: 100vh;

}
.divcontainer{
    display: flex;
    justify-content: center;

}

.forms{
    display: flex;
    flex-direction: column;
    }

.forms input{
    margin:20px;
    height: 40px;
    background-color: white;
    width:500px;
    border-radius: 50px;
    padding:20px;
    box-sizing: border-box;
}

h1{
    line-height: 10rem;
    text-align: center;
    color:white;
}

input{
font-size: 18px;
}

@media only screen and (max-width: 600px){

 .contain{
   background: red;
   margin-top:20px;
padding:20px;
width:100%;  
  }


  
.forms input{
    margin:20px;
    height: 40px;
    background-color: white;
    width:200px;
    border-radius: 50px;
    padding:20px;
    box-sizing: border-box;
}

h1{
    line-height: 5rem;
    text-align: center;
    color:white;
}

} 


@media only screen and (max-width: 450px){

.contact-us{
        width:100%;
  }


  
.forms input{
    margin:10px;
    height: 30px;
    background-color: white;
    width:200px;
    border-radius: 50px;
    padding:10px;
    box-sizing: border-box;
    font-size: 10px;
}

h1{
    line-height: 5rem;
    text-align: center;
    color:white;
}

.contact-us{
    width: 100%;
    padding:0;
    margin:0;
    background:linear-gradient(to right, #f84ab0,  #cc2b5e);
    height: 80vh;

}



} 


</style>

<div class="contact-us">
<h1>Get a free consultation</h1>
<div class="divcontainer">
  <form class="forms">
  <input type="text" id="name" placeholder="Name" />
  <input type="text" id="companyName" placeholder="Company name" />
  <input type="email" id="emaiid" placeholder="Work email-id" />
  <input type="number" id="phoneNumber" placeholder="Contact No." />
  </form>
  </div>
</div>
