<template>

<nav>
<ul>
<router-link to="/" tag="li" active-class="active" exact><a>Home</a></router-link>
<router-link to="/Team" tag="li" active-class="active" exact><a>Team</a></router-link>
</ul>
  </nav>

<!--
<ul class="nav nav-pills">
<router-link to="/" tag="li" active-class="active" exact><a>Home</a></router-link>
<router-link to="/Team" tag="li" active-class="active" exact><a>Dashboard</a></router-link>
</ul>
-->

</template>

<script>
  
export default {
    name: 'Navbar',
    data() {
       
    }
}
</script>

<style>

nav {
text-align: center;
  margin-top: 0px;
   
}
 ul {
    list-style-type: none;
    padding: 0;
  }

 li {
  
  display: inline-block;
  list-style-type: none;
  margin: 0 10px;
  }

  a {
    color: #42b983;
  }
</style>