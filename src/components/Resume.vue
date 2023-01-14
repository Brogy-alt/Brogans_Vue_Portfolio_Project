<template >

   <section id="time-line">
        <h2 class="text-center">Resume</h2>
        <div class="container py-5">
            <div class="row">
                <div class="col-md-12">
                    <div id="content" v-for="list in items" :key="list">
                        <ul class="timeline-1 text-light">
                            <li class="event">
                                <h4 class="mb-3">{{ list.title }}</h4>
                                <p>{{ list.text }}</p>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>

    </section>
 

</template>
<script scoped>
export default {
    name : 'Resume',
  
    


    data(){
        return {
            items : [
                {
                    title : 'High school',
                   text :'Matriculated at Symphony High School in 2021.',
                  
                },
                {
                    title : 'Part-time music producing',
                   text :'Spent my time producing music and improving on those skills.',
                  
                },
                {
                    title : 'Life Choices Academy',
                   text :'Currenlty studying at life choices',
                  
                }
              ]
            }
        }
        
}






</script>




<style scoped>

.resume{
    color: #FDF7FF;
}



#time-line{
  padding: 3rem;
}

.timeline-1 {
    border-left: 3px solid #89a2ba;
    border-bottom-right-radius: 4px;
    border-top-right-radius: 4px;
    background: rgba(189, 211, 226, 0.09);
    margin: 0 auto;
    position: relative;
    padding: 50px;
    list-style: none;
    text-align: left;
    max-width: 40%;
  }
  
  @media (max-width: 767px) {
    .timeline-1 {
      max-width: 98%;
      padding: 25px;
    }
  }
  
  .timeline-1 .event {
    border-bottom: 1px dashed #000;
    padding-bottom: 25px;
    margin-bottom: 25px;
    position: relative;
  }
  
  @media (max-width: 767px) {
    .timeline-1 .event {
      padding-top: 30px;
    }
  }
  
  .timeline-1 .event:last-of-type {
    padding-bottom: 0;
    margin-bottom: 0;
    border: none;
  }
  
  .timeline-1 .event:before,
  .timeline-1 .event:after {
    position: absolute;
    display: block;
    top: 0;
  }
  
  .timeline-1 .event:before {
    left: -207px;
    content: attr(data-date);
    text-align: right;
    font-weight: 100;
    font-size: 0.9em;
    min-width: 120px;
  }
  
  @media (max-width: 767px) {
    .timeline-1 .event:before {
      left: 0px;
      text-align: left;
    }
  }
  
  .timeline-1 .event:after {
    -webkit-box-shadow: 0 0 0 3px #ffffff;
    box-shadow: 0 0 0 3px #333232;
    left: -55.8px;
    background: #fff;
    border-radius: 50%;
    height: 9px;
    width: 9px;
    content: "";
    top: 5px;
  }
    
</style>