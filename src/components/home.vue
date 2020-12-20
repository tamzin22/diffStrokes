<template>

<div  class="container-fluid banner">
 <a class="navbar-brand navbar-expand-lg "><img alt="placeholder" src="../assets/lion.png" style="position:absolute;top:80px;width:100px;left:90px;"></a>
 <nav class="nav mr-1000 mx-200">
   <a class="nav-link" href="#1">Home</a>
   <a class="nav-link" href="#2">About Us</a>
   <a class="nav-link" href="#3">Get in Touch</a>
 </nav>
 <div class="nav justify-content-end mx-100">
  <a class="btn btn-outline-dark wow fadeInDown mx-2" data-wow-delay="0.4s">+254 732 743333</a>
  <a class="btn btn-outline-dark wow fadeInDown mx-2" data-wow-delay="0.4s">Book Now</a>
  <a class="btn btn-outline-dark wow fadeInDown " data-wow-delay="0.4s">Login</a>
</div>
  <p>Karibu Diff Strokes
A New Experience
to Explore Kenyan Safaris</p>
<p>With over 30 years of experience in servicing the Kenyan transport, we bring to you
a totally new experience in exploring the Kenyan Safaris.</p>
  </div>
</template>

<script>
export default {
  name:"home"
}
</script>

<style>
 .banner{
   background-image: url('../assets/giraffe.png');
   background-size: cover;
   background-repeat: no-repeat;
   margin-top: 20px;
   padding: 20px 10px;
   border: solid;
   height: 100vh;
 }

</style>