<style>

.contactus{
    width: 100%;
    padding:0;
    margin:0;
    background:linear-gradient(to right, #cc2b5e , #753a88);
    height: 100vh;

}
.divcontainer{
    display: flex;
    justify-content: center;
    padding-bottom: 50px;

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
font-size: 18px
}

@media only screen and (max-width: 600px){

 .contain{
   background: red;
   margin-top:20px;
padding:20px;
width:100vh;  
  }

  .contactus{
    width:100vh;
  }

  
.forms input{
    margin:20px;
    height: 40px;
    background-color: white;
    width:400px;
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

</style>

<div class="contactus">
<h1>Contact Us</h1>
<div class="divcontainer">
  <form class="forms">
  <input type="text" id="name" placeholder="Name" />
  <input type="text" id="companyName" placeholder="Company name" />
  <input type="email" id="emaiid" placeholder="Work email-id" />
  <input type="number" id="phoneNumber" placeholder="Contact No." />
  </form>
  </div>
</div>
