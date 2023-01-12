<template>

        <section class="container">
        
        <div class="row">
        <!-- <div class="card h-100" v-for="list in items" :key="list" style="width:25rem; margin: auto;">
          <img :src="list.img" class="card-img-top" style="height:20rem;">
          <div class="card-body" >
            <h5 class="card-title">{{ list.Project }}</h5>
            <a {{ list.Github }} class="btn btn-primary">Github</a>
            <a {{ list.Netlify }} class="btn btn-primary">Netlify</a>
            
          </div>
        </div> -->
        <div class="card" v-for="list in items" :key="list" style="width: 18rem;">
  <img class="card-img-top" :src="list.img" alt="Card image cap">
  <div class="card-body">
    <p class="card-text">{{ list.project }}</p>
    <a :href="list.github" target="_blank" class="btn btn-primary">Github</a>
    <a :href="list.netlify " target="_blank" class="btn btn-primary">Nelify</a>
  </div>
</div>
        </div>
        </section>

</template>
<script>
export default {
    name : 'Projects',

    data(){
        return {
            items : [
                {
                    img : 'https://i.postimg.cc/2yB67Kj7/Screenshot1.jpghttps://i.postimg.cc/2yB67Kj7/Screenshot1.jpg',
                    project:'Repaire website',
                    github: "https://github.com/Brogy-alt/repairwebsite.git",
                    netlify : "https://brogans-repair-site.netlify.app/ ",

                },
                {
                    img : 'https://i.postimg.cc/15G6x8Pc/Screenshot3.jpg',
                    project : 'Mini project',
                    github: "https://github.com/Brogy-alt/Mini_project.git",
                    netlify: "https://brogans-ecommerce.netlify.app/x",

                },
                {
                    img : 'https://i.postimg.cc/25chHgYs/Screenshot2.jpg"',
                    project : 'Ecommerce',
                    github : "https://github.com/Brogy-alt/Mini_project.git ",
                    netlify : "https://brogans-ecommerce.netlify.app/",

                }
                
              ]
            }
        }
}


</script>
<style>



    
</style>