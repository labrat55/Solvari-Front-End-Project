<template>

  <div class="home">
<div class="col-md-12">
    <img src="../assets/solvari.png">
   
</div>
      <router-view></router-view>

  </div>
</template>

<script>
export default {
  name: 'Index',
  data () {
    return {
      
      
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .home img{
    top:0;
    margin-left: 31%;
  }
</style>
