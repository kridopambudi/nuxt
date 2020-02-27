<template>
  <div class="container">
   <ul class="menu">   
     <li> <router-link to="/"> Depan </router-link> </li>   
     <li> <router-link to="/tentang"> Tentang </router-link> </li>   
     <li> <router-link to="/kontak"> Kontak </router-link> </li>  
   </ul>  
   <h1> Hallo, Selamat Datang :) </h1>
  </div>
</template>


<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>


<style>
.container {
   width: 75%; 
   margin: 100px auto; 
   text-align: center;
}
.menu {
  list-style: none; 
  margin-bottom: 20px;
}
.menu li { 
  display: inline;
}
.menu li a { 
  padding: 20px; 
  text-decoration: none;
}

</style>