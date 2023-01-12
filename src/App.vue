<template>
  
  <router-view/>
</template>

<style>

*,
*::after,
*::before {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    cursor:pointer;
}

/* head,
main,
footer header,
body,
footer {
    min-width: 100%;
} */


#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

h1,h2,h3,h4,h5,p{
  color: rgb(255, 255, 255);
}
body{
   
  background: linear-gradient(rgb(131, 3, 219 ), rgb(81, 27, 183));
}
</style>
