<template>
   <top-nav/>
   <main>
     <router-view/>
   </main>
 
</template>

<script>
// @ is an alias to /src

import TopNav from '@/components/TopNav.vue'

export default {
  name: 'App',
  components: {

    TopNav
  }
}
</script>

<style>
main {
    margin-left: 5rem;
    padding: 1rem;
}
body {
    color: black;
    background-color: #2a2a38;
	font-family: 'PT Sans', sans-serif;
	margin: 0;
	padding: 0;
	scroll-behavior: smooth;
  }

  body::-webkit-scrollbar {
    width: 0.25rem;
  }
  
  body::-webkit-scrollbar-track {
    background: #1e1e24;
  }
  
  body::-webkit-scrollbar-thumb {
    background: #f8a201;
  }
</style>
