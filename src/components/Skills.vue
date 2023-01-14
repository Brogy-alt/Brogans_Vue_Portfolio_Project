<template>
    
    <section class="container">

        

        <h2 class="skills-heading">My Skills</h2>

        <div class="skills-section ">
            <!-- icon links here -->
        <p style="font-size:x-large">HTML <i class="fa-brands fa-html5" style="font-size:larger"></i></p>

        <div class="container">
            <div class="skills html">75%</div>
        </div>

            <!-- icon links here -->
        <p style="font-size:x-large">CSS <i class="fa-brands fa-css3-alt" style="font-size:larger; padding-top: 1rem;"></i></p>

        <div class="container">
            <div class="skills css">70%</div>
        </div>

           
        <p style="font-size:x-large">JavaScript <i class="fa-brands fa-js" style="font-size:larger; padding-top: 1rem;"></i></p>

        <div class="container">
            <div class="skills js">55%</div>
        </div>

          <!-- icon links here -->
        <p style="font-size:x-large">Vue <i class="fa-brands fa-vuejs" style="font-size:larger; padding-top: 1rem;"></i></p>
        <div class="container">
            <div class="skills php">70%</div>
        </div>
    </div>

    </section>

</template>
<script>
export default {
    name: 'Skills'

}
</script>
<style scoped>
.container {
  width: 100%;

}

.skills {
  text-align: right;
  padding-top: 5px;
  padding-bottom: 10px;
  color: rgb(0, 0, 0);
}

.skills-section{
    padding-top:3rem;
    padding-bottom:10rem;
} 

.skills-heading{
    padding-top:1rem ;
}

.html {width: 75%; background-color: #ffffff;
    border-style: outset;
}
.css {width: 70%; background-color: #ffffff;
    border-style: outset;
}
.js {width: 55%; background-color: #ffffff;
    border-style: outset;}
.php {width: 70%; background-color: #ffffff;
    border-style: outset;}
</style>