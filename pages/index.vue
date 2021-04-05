<template>
<section class="home">
<div class="py-6 px-3">
  <div class=" mx-auto mb-5">
    <div class="w-80 mx-auto">
    <img src="~assets/img/1x1xs.png" class=" w-50 rounded-full   ">
    </div>
        <h2 class="mx-auto mt-5 text-center text-xl md:text-4xl max-w-3xl leading-tight text-gray-800 mb-12">{{page_name}}</h2>

        <h1 class="mx-auto mt-5 text-center  leading-tight text-gray-800 mb-12">
I'm a Full-Stack Developer living in Goa IN.

        </h1>


     </div>


        <p class="mb-6 text-gray-600 text-center leading-relaxed text-sm">


        </p>


<!--       <div class="grid grid-cols-1 md:grid-cols-12 gap-5">
        <div class="flex items-start">
          <img src="~assets/technologies/vuejs.png" class=" w-20 ">
        </div>
        <div class="flex items-start">
          <img src="~assets/technologies/nuxtjs.png" class=" w-20 ">
        </div>        
        <div class="flex items-start">
          <img src="~assets/technologies/django.png" class=" w-20 ">
        </div>        
        <div class="flex items-start">
          <img src="~assets/technologies/nodejs.png" class=" w-20 ">
        </div>        
        <div class="flex items-start">
          <img src="~assets/technologies/flask.png" class=" w-20 ">
        </div>        
        <div class="flex items-start">
          <img src="~assets/technologies/jquery.jpg" class=" w-20 ">
        </div>        
        <div class="flex items-start">
          <img src="~assets/technologies/javascript.jpg" class=" w-20 ">
        </div>        
        <div class="flex items-start">
          <img src="~assets/technologies/mysql.png" class=" w-20 ">
        </div>        
        <div class="flex items-start">
          <img src="~assets/technologies/bootstrap.png" class=" w-20 ">
        </div>        
        <div class="flex items-start">
          <img src="~assets/technologies/mongodb.png" class=" w-20 ">
        </div>  -->       


      </div>


    </div>
</section>

</template>

<script lang="ts">
import Vue from 'vue'
import Sidebar from "~/components/layout/sidebar.vue";
import Navbar from "~/components/layout/navbar.vue";
import Footer from "~/components/layout/footer.vue";


export default {
  components: {
    Navbar,
    Sidebar,
    Footer
  },  
  name: "Home",
  data() {
    return {
      page_name: "Pramit Sawant",
    };
  },
}
</script>

<style>

</style>
