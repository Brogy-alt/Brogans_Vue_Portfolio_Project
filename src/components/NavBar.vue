<template>
    <header>


<nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <a class="navbar-brand mt-2 mt-lg-0 text-light" style=" font-size:xx-large ; padding-left: 20px;font-family: 'Carter One', cursive;" href="/">
        
       BROGAN GYS
      </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav" style="padding-left: 13rem;" >
        <li class="nav-item" >
          <a class="nav-link active text-light" aria-current="page" href="/">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-light" href="/about">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-light" href="/resume">Resume</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-light" href="/projects">Skills</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-light" href="/testimonials">Testimonials</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-light" href="/contact">Contact</a>
        </li> 
      </ul>
    </div>
  </div>
</nav>


</header>
</template>
<script>
export default {
    name : 'NavBar'
}
</script>
<style scoped>

head,
main,
footer header,
body,
footer {
    min-width: 100%;
}

.nav-item{
    font-size: x-large;
    margin: auto;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    padding-left: 20px;

}

.logo{
    height: 3rem;
}
    
  
</style>