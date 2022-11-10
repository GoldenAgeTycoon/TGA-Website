<template>
<head>
	<title>Golden Age Tycoon | Staff</title>
</head>
<div class="slideshow-container">

  <!-- Full-width images with number and caption text -->
 <div class="mySlides fade">
    <img src="../assets/screenshots/1.png" style="width:100%">
   
  </div>

  <div class="mySlides fade">
    <img src="../assets/screenshots/2.png" style="width:100%">
   
  </div>

  <div class="mySlides fade">
    <img src="../assets/screenshots/3.png" style="width:100%">
   
  </div>

  <div class="mySlides fade">
    <img src="../assets/screenshots/4.png" style="width:100%">
   
  </div>

  <!-- Next and previous buttons -->
  <a class="prev" v-on:click="plusSlides(-1)">&#10094;</a>
  <a class="next" v-on:click="plusSlides(1)">&#10095;</a>
</div>
<br>


</template>

<script>
// @ is an alias to /src


export default {
  name: 'HomeView',
  components: {

  },
  data() {
    return {
 slideIndex: 0

    }
  },
  mounted() {
    this.showSlides();
  },
  methods: {
   plusSlides: function(n) {
  this.showSlides(this.slideIndex += n);
},

 showSlides: function(n) {
  let i;
  let slides = document.getElementsByClassName("mySlides");
 
  if (n > slides.length) {this.slideIndex = 1}
  if (n < 1) {this.slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";
  }
 
  slides[this.slideIndex-1].style.display = "block";
 
}
  }
}
</script>

<style scoped>
/* Slideshow container */
.slideshow-container {
    margin: 10px;
  margin-top: 0px;
  height: 780px;

	

}

/* Hide the images by default */
.mySlides {
 
  display: none;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  margin-top: -22px;
  padding: 16px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  animation-name: fade;
  animation-duration: 1.5s;
}

@keyframes fade {
  from {opacity: .4}
  to {opacity: 1}
}
</style>
