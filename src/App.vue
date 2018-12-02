<template>
 
  <div id="app">
  <h1>{{ title }}</h1>
 <Navbar />

   
    <router-view/>
  </div>
</template>

<script>

import Navbar from '@/components/Navbar'
import Team from '@/components/Team'

export default {
  name: 'App',
  components: {
    Navbar,
    
  },
  data() {
    return {
    title: 'Menu'
        }
  }
   
}
</script>

<style>
  h1{
    color: #444;
    font-weight: normal;
    text-align: center;
    font-size: 2.0rem;
    margin-top: 100px;
  
  }
</style>
