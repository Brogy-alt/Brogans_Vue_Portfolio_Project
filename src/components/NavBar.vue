<template>
    <header class="">
        <!-- <nav class="navbar navbar-expand-lg bg-light text-light ">
            <div class="container-fluid">
                <a class="navbar-brand" href="index.html">
                    <img class="logo" src="https://i.postimg.cc/VLjZH31V/speakerlogo.png" alt="logo" width="60" height="55">
                </a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                    data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent"
                    aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav ms-auto mb-2 mb-lg-0 ">
                        <li class="nav-item">
                            
                            <a class="nav-link active" aria-current="home-nav" href="/"> <i class="fa-sharp fa-solid fa-house-user"></i> Home</a>
                        </li>
                        <a class="nav-link active" aria-current="aboutme-nav" href="/about">About me</a>

                        <a class="nav-link active" aria-current="aboutme-nav" href="/resume">Resume</a>

                        <a class="nav-link active" aria-current="aboutme-nav" href="/projects">Projects</a>

                        <a class="nav-link active" aria-current="aboutme-nav" href="/skills">Skills</a>

                        <a class="nav-link active" aria-current="aboutme-nav" href="/testimonials">Testimonials</a>

                          
                        
                        <a class="nav-link active" aria-current="contact-nav" href="/contact"> <i class="fa-solid fa-phone"></i>Contact & Socials</a>
                        
                        <li class="nav-item">
                            <a class="nav-link"></a>
                        </li>
                    </ul>
                </div>
            </div>
            </nav> -->
    

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <!-- Container wrapper -->
  <div class="container-fluid">
    <!-- Toggle button -->
    <button
      class="navbar-toggler"
      type="button"
      data-mdb-toggle="collapse"
      data-mdb-target="#navbarSupportedContent"
      aria-controls="navbarSupportedContent"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <i class="fas fa-bars"></i>
    </button>

    <!-- Collapsible wrapper -->
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <!-- Navbar brand -->
      <a class="navbar-brand mt-2 mt-lg-0" href="#">
        <img class="logo"
          src="https://i.postimg.cc/VLjZH31V/speakerlogo.png"
          height="15"
          alt="MDB Logo"
          loading="lazy"
        />
      </a>
      <!-- Left links -->
      <ul class="navbar-nav me-auto mb-2 mb-lg-0 mx-auto" >

        <li class="nav-item" >
          <a class="nav-link" href="/">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/about">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/resume">Resume</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/projects">Projects</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/skills">Skills</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/testimonials">Testimonails</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/contact">Contact</a>
        </li>
      </ul>
      <!-- Left links -->
    </div>
    <!-- Collapsible wrapper -->

    <!-- Right elements -->
    
    <!-- Right elements -->
  </div>
  <!-- Container wrapper -->
</nav>
<!-- Navbar -->

</header>
</template>
<script>
export default {
    name : 'NavBar'
}
</script>
<style>

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