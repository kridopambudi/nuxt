<template> 
  <div class="container">  
    <ul class="menu">   
      <li> <router-link to="/"> Depan </router-link> </li>   
      <li> <router-link to="/tentang"> Tentang </router-link> </li>   
      <li> <router-link to="/kontak"> Kontak </router-link> </li>  
    </ul>  
    <section class="content">  
      <p> Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
        quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
        consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
        cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
        proident, sunt in culpa qui officia deserunt mollit anim id est laborum. 
      </p>  
    </section> 
  </div>
</template>


<script>
export default {
  }
</script>


<style scoped>
.container { 
  width: 75%; 
  margin: 100px auto; 
  text-align: center;
}
.content p { 
  text-align: justify;
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