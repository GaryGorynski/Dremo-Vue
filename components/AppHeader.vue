<template>
  <div>
       <header class="header">
        <nav class="nav">
         <div class="nav__logo">Dre<span class="nav__logo-span">mo</span></div> 
          <ul class="nav__links">
           <li>
            <a class="home" href="#">Home</a>
           </li>
           <li>
            <a class="btn" href="#" style="color: rgb(248, 235, 235);">Find Home</a>
           </li>
           <li> 
            <a href="#">About us</a>
           </li>
           <li>
            <a href="#">Location</a>
           </li>
           <li>
            <a href="#">Reviews</a>
           </li>
           <li>
            <a href="#">Sign in</a>
           </li>
          </ul>
        </nav>
    </header>   
  </div>
</template>

<script>
export default {
name: 'AppHeader'
}
</script>

<style>
nav {
    display: flex;
    padding-top: 50px;
    justify-content: space-around;
    align-items: center;
    min-height: 8vh;
    font-family: 'Poppins', sans-serif;  
      

}

 .nav__logo {
    font-family: Poppins;
font-style: normal;
font-weight: 500;
font-size: 36px;
color: #4270C9;
flex: 1;
margin-left: 94px;

}

.nav__logo-span {
    color: black;
}
 
.btn {
    padding: 12px 25px;
    background-color:#4270C9;
    border:none;
    border-radius: 50px;
    cursor: pointer;
    
    
}
.nav__links {
    display: flex;
    justify-content: space-around;
    width: 40%;
    align-items: center;
    padding: 5px;
    margin-right: 123px;
   
    
}
.nav__links li {
    list-style: none;
    
}
.nav__links a {
    color: black;
    text-decoration: none;
}
</style>