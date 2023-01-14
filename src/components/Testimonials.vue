<template>
    

    <h2 class="text-center">Testimonials</h2>
        
        <div class="testi">

           
            
            <div class="row">
                <div class="card bg-dark h-100 col-4" v-for="list in items" :key="list" style="width:25rem;height:25rem; margin: auto;">
                    <img :src="list.img" class="card-img-top img-fluid" style="height:20rem;padding: 30px;width: 100%;">
                    <div class="card-body" >
                        <h5 class="card-title text-light">{{ list.Person }}</h5>
                        <p class="card-text text-light">{{ list.Comment }}.</p>
                       
                    </div>
                </div>
            
        </div>
    </div>
    



</template>
<script>
export default {
    name : 'Testimonials',

    data(){
        return {
            items : [
                {
                    img : 'https://i.postimg.cc/GhSShNPq/t1.jpg',
                    Person : 'Meezaan',
                    Comment : ' Brogan has a really bright and innovative mind when it comes to the design of his projects. Brogan to the eye is very introverted but once he opens up he is totally the opposite.',

                },
                {
                    img : 'https://i.postimg.cc/T3h9Mgd5/t0.jpg',
                    Person : 'Imraan',
                    Comment : ' Brogan has a good judge of character, he is a very friendly person to be around.He is also very passionate about his music producing, I view him as a smart and knowledgeable guy.',

                },
                {
                    img : 'https://i.postimg.cc/KzFW4QHc/Lazola.jpg',
                    Person : 'Lazola',
                    Comment : 'Brogan likes learning new stuff, he is a team player and he also brings new ideas to projects. I can assure you that he can be a great asset to your company',

                },
                {
                    img : 'https://i.postimg.cc/Px3Mh4GR/Joel-Profile.jpg',
                    Person : 'Joel Mukanya (Lecturer)',
                    Comment : 'Brogan is a very creative, go-getter, and well-behaved student. He does He has gained knowledge of web development, including Bootstrap 5',

                },
                {
                    img : 'https://i.postimg.cc/kMLxcD7K/Asandile.jpg',
                    Person : 'Asandile',
                    Comment : 'Brogan is =someone who knows how to stick to the task at hand and is willing to help where he can. He loves his space and he is respectful towards others',

                },
                {
                    img : 'https://i.postimg.cc/DZCh0QV8/Cassidy.png',
                    Person : 'Cassidy',
                    Comment : 'Brogan is an extremely committed worker. He doesnt let go of his attention till the job is done. He works well with others as a team and is always eager to lend a hand when needed.',

                }
            ]
            }
        }
}

</script>
<style scoped>

.testi{

    padding:7rem ;
}

@media (max-width: 500px) {
   
   .card {
       scale: 0,4;
   }

}
@media (max-width: 400px) {
   
   .card {
       scale: 0,2;
   }

}
@media (max-width: 300px) {
   
   .card {
       scale: 0,2;
   }

}
@media (max-width: 300px) {
   
   .card {
       scale: 0,2;
   }

}



</style>