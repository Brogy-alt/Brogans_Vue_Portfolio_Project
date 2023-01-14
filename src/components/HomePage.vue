<template>
  <main>

    <!--Home-->
    <section id="home" class="container min-vh-100">
      <div class="row d-flex flex-column flex-md-row ">

        <!-- Section One -->

        <section class="section-one">
          <h2 class="header-home">Welcome To My Portfolio</h2>

          <h4 class="header-home-2">Aspiring Web developer</h4>
          <h4 class="header-home-3">Music Producer</h4>
          
          <!-- Offcanvas thing for socials -->

          <div class="btn-socials">

          <button class="btn btn-outline-light" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasExample"
            aria-controls="offcanvasExample">
            Reach out to me
          </button>
        </div>

          <div class="offcanvas offcanvas-start" tabindex="-1" id="offcanvasExample"
            aria-labelledby="offcanvasExampleLabel">
            <div class="offcanvas-header">
              <h5 class="offcanvas-title" id="offcanvasExampleLabel">Offcanvas</h5>
              <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
            </div>
            <div class="offcanvas-body">
              <div>
                Open the dropdown below to get access to my links
              </div>
              <div class="dropdown mt-3">
                <button class="btn btn-secondary dropdown-toggle" type="button" data-bs-toggle="dropdown">
                  Click me
                </button>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="https://www.instagram.com/prodbrogy/" target="_blank"><i class="fa-brands fa-instagram"></i>Instagram</a> </li>
                  <li><a class="dropdown-item" href="https://www.youtube.com/@prodbrogy/featured" target="_blank"><i class="fa-brands fa-youtube"></i>Youtube</a></li>
                  <li><a class="dropdown-item" href="https://github.com/" target="_blank"><i class="fa-brands fa-github"></i>Github</a></li>
                </ul>
              </div>
            </div>
          </div>

        </section>
        
      </div>
    </section>

  </main>
</template>

<script>
export default {
  name: 'HomePage'

}
</script>


<style scoped>

main {

  background: url(https://i.postimg.cc/1zMNgtfb/maxim-berg-6-NP-Cd-Nqt-U-unsplash.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  width:100%

}



section {
  padding: 10px 0rem;
}

.section-one {
  /* margin: 11rem 2rem 0; */
  width: 100%;
  

}


.header-home-2 {
  font-size: 2rem;
}

.section-one-paragraph {
  margin: 2rem 0;
  width: 90%;
  max-width: 500px;

}

.header-home{
  padding-top: 10rem;
  text-align: center;
  animation-name: fade-in;
  animation-duration: 5s;
  font-size: 5.5rem;
  width: 100%;
}

.header-home-2 {
  padding: 1rem;
  text-align: center;
  animation-name: fade-in;
  animation-duration: 7s;
}

.header-home-3 {
  padding: 1rem;
  text-align: center;
  animation-name: fade-in;
  animation-duration: 9s;
}

.btn {
  padding: 1rem;
  text-align: center;
  animation-name: fade-in;
  animation-duration: 10s;
}

.btn-socials{
  padding-bottom: 5rem;
}



@keyframes fade-in {
  from {
    opacity: 0;
  }

  to {
    opacity: 1;
  }
}

@media (max-width:300px) {
  .header-home {
    padding-top: 2rem;
  }
  
}
</style>