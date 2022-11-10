<template>
<head>
	<title>Golden Age Tycoon | Join</title>
</head>

<div class="join">
<header id="head" class="parallax">
<h1 class="border" >Join</h1>
<h2 class="border" >play.goldenagetycoon.com</h2>
<container class="container">

    <card class="card"> 
      <h1 class="site-text">Technic</h1>
      <img src="../assets/techniclogo.png" alt="Technic logo">
      <h2 class="site-text"><br>A technic pack is currently in the works please check back later</h2>
    </card>

    <card class="card">
      <h1 class="site-text">Curse</h1>
      <img src="../assets/curse.png"  alt="Curse logo">
      <h2 class="site-text"><br>Curse forge install instrictions are in the <a href="https://discord.gg/KjkV7gheXB" target="_blank" rel="noopener noreferrer" >Discord</a> in #how-to-install OR search "Golden Age Tycoon 2" on curse!</h2>
    </card>

 

   </container>
</header>
<!-- End Header -->
<!-- About Section -->

</div>
</template>

<script>
// @ is an alias to /src


export default {
  name: 'HomeView',
  components: {

  }
}
</script>

<style scoped>
 .site-text {
   color: #b6b6b6;
 }
 .border {
     text-shadow: -1px 0 #f8a201, 0 1px #f8a201, 1px 0 #f8a201, 0 -1px #f8a201;

 }
#head {

	background-image: url("../assets/2.png");
  width: 100%;
  height: 500px;
	margin: 0;
	padding: 200px 0px 200px 0px;
	text-align: center;

}

#head h1 {
	font-size: 55px;
	font-weight: 700;
	text-transform: uppercase;
}

#head h2 {
	font-size: 22px;
	text-transform: uppercase;
    
}

  .container {
    padding: 2px 16px;
  }

    .container {
    max-width: 100vw;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    grid-gap: 35px;
    margin: 0 auto;
    padding: 40px 0;
  }
    .card {
      text-align: center;
      position: relative;
      width: 325px;
      height: 425px;
      margin: 0 auto;
      background: #2a2a38;
      border-radius: 15px;
      box-shadow: 0 15px 60px rgba(0, 0, 0, 0.5);
    }
</style>
