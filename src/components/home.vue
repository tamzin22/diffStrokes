<template>
<div class="container-fluid" >
  
     
<div class="row" style="margin-top:20px"  >
<div class="card-navba" >
<b-nav id="nav" >
<div class="top-left position-absolute"><b-nav-item href="#1">Home</b-nav-item></div>
<div class="about position-absolute"><b-nav-item href="#2">About Us</b-nav-item></div>
<div class="inTouch"><b-nav-item href="#3">Get in Touch</b-nav-item></div>
<div class="contact"><b-nav-item href="#4">+254 732 743333</b-nav-item></div>
<div class="book"><b-nav-item href="#5">Book Now</b-nav-item></div>
<div class="login"><b-nav-item href="#6">Login</b-nav-item></div>
</b-nav>
<img alt="placeholder" src="../assets/giraffe.png" class="img-thumbnail" style="width: 100%; border:solid; " >

<p class= "par">Karibu Diff Strokes</p>
<p class="card-text">A New Experience
to Explore Kenyan Safaris</p>
<p class="card-text">With over 30 years of experience in servicing the Kenyan transport, we bring to you
a totally new experience in exploring the Kenyan Safaris.</p>
<b-nav id="navy">
<div class="safari"><b-nav-item href="#1">Safari Car Hire</b-nav-item></div>
<div class="luxury"><b-nav-item href="#2">Luxury Car Hire</b-nav-item></div>
<div class="tours"><b-nav-item href="#3">City Tours</b-nav-item></div>
</b-nav>

  </div>
</div>

</div>

</template>

<script>
 export default{
 name : "home"
 }
</script>

<style>
 .safari {
  position: absolute;
  top: 800px;
  left: 100px;
  color:white;
}
.luxury {
  position: absolute;
  top: 800px;
  left: 400px;
  color:white;
}
.tours{
  position: absolute;
  top: 800px;
  left: 800px;
  color:white;
}
.saf{
  margin-left: 50%;
}
.top-left{
  position: absolute;
  top: 100px;
  left: 300px;
  color:white;
}
.about{
  position: absolute;
  top: 100px;
  left: 400px;
  color:white;
}

.inTouch{
  position: absolute;
  top: 100px;
  left: 500px;
  color:white;
}
</style>
