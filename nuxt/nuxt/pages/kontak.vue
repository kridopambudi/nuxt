<template>
	<div class="container">  
		<ul class="menu">    
		  <li> <router-link to="/"> Depan </router-link> </li>   
	      <li> <router-link to="/tentang"> Tentang </router-link> </li>   
	      <li> <router-link to="/kontak"> Kontak </router-link> </li>
		</ul>
		<h1> Kontak </h1>  
	 	   <ul class="contact">
	 	   	<li><a href="https://linkedin.com/kridopambudi"> LikedIn </a></li> 
	 	   	<li><a href="https://twitter.com/kridopb"> Twitter </a></li>  
	 	   	<li><a href="https://instagram.com/kridopb"> Instagram </a></li>
	 	   	<li><a href="https://github.com/kridopambudi"> GitHub </a></li> 
	 	   </ul>
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
h1 { margin-bottom:20px;
}
.menu { 
	list-style: none; 
	margin-bottom: 20px;
}
.menu li,.contact li { 
	display: inline;
	margin : 5px;
	text-decoration: none;

}
.menu li a { 
	padding: 20px; 
	text-decoration: none;
}
.contact { 
	list-style: none;
}
</style>