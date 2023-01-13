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

          <button class="btn btn-outline-light" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasExample"
            aria-controls="offcanvasExample">
            Reach out to me
          </button>

          <div class="offcanvas offcanvas-start" tabindex="-1" id="offcanvasExample"
            aria-labelledby="offcanvasExampleLabel">
            <div class="offcanvas-header">
              <h5 class="offcanvas-title" id="offcanvasExampleLabel">Offcanvas</h5>
              <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
            </div>
            <div class="offcanvas-body">
              <div>
                Some text as placeholder. In real life you can have the elements you have chosen. Like, text, images,
                lists, etc.
              </div>
              <div class="dropdown mt-3">
                <button class="btn btn-secondary dropdown-toggle" type="button" data-bs-toggle="dropdown">
                  Dropdown button
                </button>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Action</a></li>
                  <li><a class="dropdown-item" href="#">Another action</a></li>
                  <li><a class="dropdown-item" href="#">Something else here</a></li>
                </ul>
              </div>
            </div>
          </div>

        </section>

        <!-- <div class=" home-text col">
                    <h1 class="name lead ">Brogan Gys</h1>
                    <h5 class="lead">Aspiring developer</h5>
                    <h5 class="lead">Music producer</h5>
                </div> -->
        <!-- <div class="col">
                    <img src="https://i.postimg.cc/Zn4hrwKW/C11-Brogan-Gys-3.jpg" style="max-width: 60%; height: 50;"
                        alt="Brogans Profile" class="rounded mx-auto d-block">
                        <div class="pt-3">
                        <center>
                            <a class="btn btn-lg btn-floating border-light text-light" href="https://www.instagram.com/prodbrogy/" target="_blank" role="button"><i class="fab fa-instagram"></i>
                            </a>
                            <a class="btn btn-lg btn-floating border-light text-light" href="https://twitter.com/_Brogy_ " target="_blank" role="button"><i class="fab fa-twitter"></i>
                            </a>
                            <a class="btn btn-lg btn-floating border-light text-light" href="https://www.youtube.com/channel/UC13tr7mMjdQfZRaoI0rbTgQ" target="_blank" role="button"><i class="fab fa-youtube"></i>
                            </a>
                            
                        </center>
                    </div>
                </div> -->
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

}

#home {
  padding: 10px 0rem;
}

.section-one {
  margin: 11rem 2rem 0;

}

.header-home {
  font-size: 5.5rem;
}

.header-home-2 {
  font-size: 2rem;
}

.section-one-paragraph {
  margin: 2rem 0;
  width: 90%;
  max-width: 500px;

}

.header-home {
  padding: 1rem;
  text-align: center;
  animation-name: fade-in;
  animation-duration: 5s;
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

@keyframes fade-in {
  from {
    opacity: 0;
  }

  to {
    opacity: 1;
  }
}
</style>