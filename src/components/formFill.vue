<template>
    <div>
     <b-nav>   
            <img src="../assets/lion.png" alt="Logo" style="width:40px;">
<div class="top-left position-absolute"><b-nav-item href="#1">Home</b-nav-item></div>
<div class="about position-absolute"><b-nav-item href="#2">About Us</b-nav-item></div>
<div class="inTouch"><b-nav-item href="#3">Get in Touch</b-nav-item></div>
<div class="contact"><b-nav-item href="#4">+254 732 743333</b-nav-item></div>
<div class="book"><b-nav-item href="#5">Book Now</b-nav-item></div>
<div class="login"><b-nav-item href="#6">Login</b-nav-item></div>
</b-nav>
   <img alt="Vue logo" src="../assets/cars.png" class="img-thumbnail" style="width: 100%;"> 
   
  <div class="card col-md-8 col-md-8 col-m-8" style="margin-top:-50px;">
    <div class="row">
      <div class="col-md">
  <form >
  <div class="form-row justify-content-center">
    <div class="form-group col-md-6 ">
      <label for="inputName4">Name</label>
      <input type="text" class="form-control" id="inputName4" >
    </div>
    <div class="form-group col-md-6">
      <label for="inputEmail4">Phone</label>
      <input type="number" class="form-control" id="inputPhone4" >
    </div>
    <div class="form-group col-md-6">
      <label for="inputEmail4">Email</label>
      <input type="email" class="form-control" id="inputEmail4">
    </div>
     <div class="form-group col-md-6">
      <label for="inputDate4">Booking Date</label>
      <input type="date" class="form-control" id="inputDate4" >
    </div>
    <div class="form-group col-md-6">
      <label for="inputpass4">No. of Passangers</label>
      <input type="number" class="form-control" id="inputPass4">
    </div>
    <div class="form-group col-md-6">
      <label for="inputPickUp4">Pick up Point</label>
      <input type="text" class="form-control" id="inputPickUp4">
    </div>
    <div class="form-group col-md-6">
      <label for="inputDes4">Destination</label>
      <input type="text" class="form-control" id="inputDes4">
    </div>
    <div class="form-group col-md-6">
      <label for="inputVehicle">Type of Vehicle</label>
      <select id="inputVehicle" class="form-control">
        <option selected></option>
        <option>...</option>
      </select>
    </div>
      <button type="submit" class="btn btn-grey">Submit</button>
  </div>
   </form>
      </div>
      <div class="col-md" style="background-color:grey;">
         <h1>Contact Information</h1>
         <p>+254 732 743333</p>
         <p>info@diffstrokes.com</p>
         <img src="../assets/lion.png" alt="Logo" >
      </div>
      </div>
   </div>
    </div>
</template>
<script>
export default {
    name:"formFill"
}
</script>
