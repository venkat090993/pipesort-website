<style>

.contactus{
    width: 100%;
    padding:0;
    margin:0;

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
}

</style>

<div class="contactus">
<h1>Contact Us</h1>
<div class="divcontainer">
  <form class="forms">
  <input type="text" id="name" placeholder="Name" />
  <input type="text" id="companyName" placeholder="Company name" />
  <input type="text" id="emaiid" placeholder="Work email-id" />
  <input type="text" id="phoneNumber" placeholder="Contact No." />
  </form>
  </div>
</div>
