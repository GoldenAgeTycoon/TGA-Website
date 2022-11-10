<template>
<head>
	<title>Golden Age Tycoon</title>
</head>
<div class="home">
<header id="head" class="parallax">
<h1>Golden Age Tycoon</h1>
<h2>play.goldenagetycoon.com</h2>
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
#head {

	background-image: url("../assets/headimage.png");
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
     text-shadow: -1px 0 #f8a201, 0 1px #f8a201, 1px 0 #f8a201, 0 -1px #f8a201;
}

#head h2 {
	font-size: 22px;
	text-transform: uppercase;
     text-shadow: -1px 0 #f8a201, 0 1px #f8a201, 1px 0 #f8a201, 0 -1px #f8a201;
}

</style>
