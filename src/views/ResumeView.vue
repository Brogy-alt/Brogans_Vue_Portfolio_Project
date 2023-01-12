<template>
    <NavBar/>
    <Resume/>
    <Footer/>
    
   
 </template>
 <script>
 import NavBar from '@/components/NavBar.vue'
 import Footer from '@/components/Footer.vue'
 import Resume from '@/components/Resume.vue'
 
 export default {
   name: 'HomeView',
   components: {
    
     Resume,
   
   }
 }
 
 </script>
 
 