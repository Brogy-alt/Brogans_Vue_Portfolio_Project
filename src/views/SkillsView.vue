<template>
    <NavBar/>
    <Skills/>
    <Footer/>
    
    
   
 </template>
 <script>
 import NavBar from '@/components/NavBar.vue'
 import Footer from '@/components/Footer.vue'
 import Skills from '@/components/Skills.vue'
 
 export default {
   name: 'HomeView',
   components: {
     NavBar,
     Skills,
     Footer
   }
 }
 
 </script>
 
 z