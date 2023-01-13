<template>
    
    <section class="container">

        

        <h2 class="skills-heading">My Skills</h2>

        <div class="skills-section ">
        <p>HTML</p>
        <div class="container">
            <div class="skills html">75%</div>
        </div>

        <p>CSS</p>
        <div class="container">
            <div class="skills css">70%</div>
        </div>

        <p>JavaScript</p>
        <div class="container">
            <div class="skills js">55%</div>
        </div>

        <p>Vue</p>
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
  padding-top: 10px;
  padding-bottom: 10px;
  color: rgb(0, 0, 0);
}

.skills-section{
    padding-top:3rem;
    padding-bottom:10rem;
} 

.skills-heading{
    padding-top:3rem ;
}

.html {width: 75%; background-color: #ffffff;}
.css {width: 70%; background-color: #ffffff;}
.js {width: 55%; background-color: #ffffff;}
.php {width: 70%; background-color: #ffffff;}
</style>