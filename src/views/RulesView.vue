<template>
<head>
	<title>Golden Age Tycoon | Rules</title>
</head>
<div class="rules">
 <header >
      <h1 class="site-text light">SERVER RULES</h1>
          <h3 class="site-text light">1. Left hand drive please
<br>
<br>
2. Obey signs along the route, they are there for a reason. If you want people to go slowly in your base area, use Traffic Control signs to signify. This is to avoid damage to stations, end-of-line buffers, collision with other people's stock etc.
<br>
<br>
3. If you accidentally break track, let me know with coords so I can repair it.
<br>
<br>
4. If you grief others in any way you will be banned.
<br>
<br>
4b. Please report all methods of duplication/infinite item methods that you find. Nonharmful things such as automating fuel production, a food, or a resource you're going to use for building or crafting are fine. Anything with the purpose to break the economy and profit off of is bannable. If you want to sell items, there's more info in 🏭shop-info🏭 
<br>
<br>
5. Please don't take or drive others' trains. This includes wrestling controls with other players. You can use the stock assigner to assign your name to stock, and holding Paperwork will show who's stock belongs to who.
<br>
<br>
5b Following on, don't push other people's trains down the lines unless they ask for it.
<br>

<br>
6. Having any creative items at your survival base is terms for an immediate ban.
<br>
<br>
7. One last thing. Please don't leave locos on the mainline if you have to go offline. The mainlines can be busy and need to be free for use by all players. If no sidings are nearby, pick it up please! </h3>

 </header>

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
hr{
  height: 1px;
  background-color: #f8a201;
  border: 0px;
}
#head {
	margin: 10px;
  margin-top: 0px;
  height: 795px;
	text-align: center;
	padding-top: 33px;
	padding-bottom: 66px;
  background-image: url("../assets/3.png");
}

#rules h1 {
	font-size: 30px;
	font-weight: 700;
	text-transform: uppercase;
	margin-top: 15px;
  color: #b6b6b6;
}

#staff h2 {
	margin-top: 5px;
	font-size: 20px;
  color: #b6b6b6;
}
h3 {
    color: #ececec;
}
#staff p {
	margin-top: 3px;
	font-size: 18px;
  color: #b6b6b6;

}

#staff .stafflist {
	max-width: 1280px;
	margin: 0 auto;
	padding-top: 66px;
}

#staff .stafflist2 {
	max-width: 1280px;
	margin: 0 auto;
	padding-top: 33px;
}

#staff .staffblock {
	transform: none;
	transition: all .2s ease-in;
	margin-bottom: 5px;
}

#staff .staffblock:hover {
	transform: scale(1.1,1.1);
	transition: all .2s ease-in;
}
.col-md {
    -ms-flex-preferred-size: 0;
    flex-basis: 0;
    -webkit-box-flex: 1;
    -ms-flex-positive: 1;
    flex-grow: 1;
    max-width: 100%;
}
.row {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
    margin-right: -15px;
    margin-left: -15px;
}
#staff h1.dark {


  color: #1f1f1f
}
 #staff p.dark {

  color: #1f1f1f
}
.light {
    color: #b6b6b6;
}
</style>
