<template>
   <NavBar/>
   <Projects/>
   <Footer/>
   
  
</template>
<script>
import NavBar from '@/components/NavBar.vue'
import Footer from '@/components/Footer.vue'
import Projects from '@/components/Projects.vue'

export default {
  name: 'HomeView',
  components: {
    NavBar,
    Projects,
    Footer
  }
}

</script>