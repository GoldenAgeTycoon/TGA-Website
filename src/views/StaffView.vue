<template>
<head>
	<title>Golden Age Tycoon | Staff</title>
</head>
<div class="staff">
 <section id="staff">
          <h1 class="site-text dark">OUR STAFF</h1>
          <p class="site-text dark">The staff members of our server</p>
          <!-- First Row Staff -->
          <div class="row stafflist2">
            <!-- First Staff Member -->
            <div class="col-md staffblock">
              <img width="100px;" height="100px;" src="../assets/shibanu.png" alt="Server owner">
              <h2 class="site-text">Shibanu</h2>
              
              <p class="site-text">Owner</p>
            </div>
            <!-- End First Staff Member -->
      
            <!-- Second Staff Member -->
            <div class="col-md staffblock">
              <img width="100px;" height="100px;" src="../assets/Aerin.png" alt="Server Co-Owner">
              <h2 class="site-text">Aerin_Hunter</h2>
              <p class="site-text">Co-Owner</p>
            </div>
            <!-- End Second Staf Member -->
      
            
            <!-- End Third Staff Member -->
          </div>
          <!-- End First Row Staff -->
      
          <!-- Second Row Staff Member -->
          <div class="row stafflist">
            <!-- Fourth Staff Member -->
            <div class="col-md staffblock">
              <img width="100px;" height="100px;" src="../assets/agentv9.png" alt="Server moderator">
              <h2>agentv9</h2>
              <p>Moderator</p>
            </div>

             <div class="col-md staffblock">
              <img width="100px;" height="100px;" src="../assets/Firebird.png" alt="Server moderator">
              <h2>Firebird4312</h2>
              <p>Moderator</p>
            </div>
              <div class="col-md staffblock">
              <img width="100px;" height="100px;" src="../assets/Jake.png" alt="Server moderator">
              <h2>JakeD20</h2>
              <p>Retired owner / Moderator</p>
            </div>
          </div>
      
          <div class="row stafflist">
            <!-- Fourth Staff Member -->
             <div class="col-md staffblock">
              <img width="100px;" height="100px;" src="../assets/Noctis.png" alt="Server moderator">
              <h2>NoctisProduction</h2>
              <p>Builder</p>
            </div>
            <!-- End Fourth Staff Member -->
      
            <!-- Fifth Staff Member -->	
             <div class="col-md staffblock">
              <img width="100px;" height="100px;" src="../assets/Danieru2.png" alt="Server moderator">
              <h2>Danieru2</h2>
              <p>Builder</p>
            </div>
            <!-- End Fifth Staff Member -->
       <div class="col-md staffblock">
              <img width="100px;" height="100px;" src="../assets/Sonic.png" alt="Server moderator">
              <h2>Sonicsong187</h2>
              <p>TrackMaster</p>
            </div>
            <!-- Sixth Staff Member -->
          
          </div>
          <!-- End Second Row Staff -->
        </section>

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
#staff {
  
	margin: 10px;
  margin-top: 0px;
  height: 795px;
	text-align: center;
	padding-top: 33px;
	padding-bottom: 66px;
  background-image: url("../assets/1.png");
}

#staff h1 {
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
</style>
