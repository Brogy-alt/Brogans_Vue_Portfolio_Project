<template>

        <div class="projects">
        <div class="row">
    
        <div class="card bg-dark mx-auto" v-for="list in items" :key="list" style="width: 25rem;">
  <img class="card-img-top" :src="list.img" alt="Card image cap">
  <div class="card-body">
    <p class="card-text">{{ list.project }}</p>
    <a :href="list.github" target="_blank" class="btn btn-outline-light ">Github</a>
    <a :href="list.netlify " target="_blank" class="btn btn-outline-light">Nelify</a>
  </div>
</div>
        </div>
    </div>


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
                
                
                ,
                {
                    img : 'https://i.postimg.cc/cHyt8Vvj/Js-project.jpg',
                    project : 'Javascript Ecommerce Project',
                    github : " https://github.com/Brogy-alt/Javascript_Final_Project.git",
                    netlify : "https://brogans-javascript-project.netlify.app/",

                },
                {
                    img : 'https://i.postimg.cc/25cmsvDx/cally.jpg',
                    project : 'Javascript Calculator',
                    github : "https://github.com/Brogy-alt/My_calculator.git",
                    netlify : "https://brogan-calculator.netlify.app"
                },
                {
                    img : 'https://i.postimg.cc/5NzsDFvW/Screenshot-2023-01-13-095728.jpg',
                    project : 'Random User Javascript',
                    github : "https://github.com/Brogy-alt/Random_user.git",
                    netlify : "https://my-random-user-js.netlify.app/",

                }
                
              ]
            }
        }
        
}


</script>
<style scoped>




.row{
    padding-top: 5rem ;
}
    
.projects{

    padding-bottom: 9rem;
}

</style>