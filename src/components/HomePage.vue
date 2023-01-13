<template>
    <main>

        <!--Home-->
        <section id="home" class="container min-vh-100">
            <div class="row d-flex flex-column flex-md-row ">

                <!-- Section One -->

                <section class="section-one">
                    <h2 class="header-home">Welcome To My Portfolio</h2>
                    <h3 class="header-home-2">Aspiring Web developer</h3>
                    
                   
                    <!-- <h3 class="section-one-paragraph">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quasi laborum quis obcaecati fugiat illo velit, sunt molestias aut repellat explicabo cum blanditiis necessitatibus asperiores eveniet debitis ducimus illum consectetur? Debitis.</h3> -->
                    <!-- <a href="" class="learn-more-btn">Learn More </a> -->
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
section {
    padding: 10px 0rem;
}



main {

    background: url(https://i.postimg.cc/1zMNgtfb/maxim-berg-6-NP-Cd-Nqt-U-unsplash.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;

}



section {
    padding: 10px 0rem;
}

.section-one {
  margin: 11rem 2rem 0;
    
}

.header-home {
  font-size: 5.5rem;
}

.header-home-2 {
  font-size: 2.5rem;
}

.section-one-paragraph {
  margin: 2rem 0;
  width: 90%;
  max-width: 500px;
  
}

.header-home, .header-home-2 {
  padding: 1rem;
  text-align: center;
  animation-name: fade-in;
  animation-duration: 5s;
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