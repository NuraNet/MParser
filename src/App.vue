<template>
  <div id="app">
    <router-view/>
      <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </nav>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Arima+Madurai:wght@200&family=Cairo:wght@200&family=Goldman&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Baloo+2&display=swap');

h1,h2{ 
  font-family: 'Goldman', cursive;
  text-align: center;
  color: black;
  font-size: 2rem;
  margin:1%;

}

.logo {
 
  width:20rem;
  text-align: center;
  border-color: #000;
  color: black;
  border: 1px solid black;
  margin: auto;
  border-radius: 10px;
  

}

#nav {
  padding: 10px;
}

a:link,a:visited {
 color: blue;
 text-decoration: none;
}

#nav a {
 color: blue;
 text-decoration: none;
 padding: 10px;
 border-radius: 4px;
 margin: 100px auto;
 
}


#nav a.router-link-exact-active {
  color: white;
  text-decoration: none;
  background-color: black;
  border-radius: 4px;
  padding: 5px;
}



body {
  font-family: 'Baloo 2', cursive;
  font-size:1.2rem;
  text-align: center;
}



 .container {
   max-width: 700px;
   margin: 100px auto;
   overflow: auto;
   
   border: 1px solid steelblue;
   padding: 10px;
   border-radius: 5px;
   box-shadow: 30px 0px 40px rgba(0,0,0,0.1),-30px 0 40px rgba(0,0,0,0.1);
   text-align: center;
  

   font-family: 'Baloo 2', cursive;
   font-size:1.2rem
  
 }


 .button {
    display: inline-block;
    background: #000;
    color: #fff;
    border: none;
    padding: 10px 20px;
    margin: 5px;
    border-radius: 50px;
    cursor: pointer;
    text-decoration: none;
    font-size: 1rem;
    font-family: inherit;
    transition: background 500ms ease;

 }
 .button:hover {
      background: gray;
  }
  
</style>