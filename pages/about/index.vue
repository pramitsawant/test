<template>
<section class="home">
<div class="py-12 px-3">
      
      <div class="max-w-6xl mx-auto mb-6">
        
        <h2 class="mx-auto text-center text-2xl md:text-5xl max-w-3xl leading-tight text-gray-800 mb-12">{{page_name}}</h2>


   

      </div>



      <div class="max-w-5xl mx-auto flex flex-wrap items-start">
        
<!--         <div class="w-full md:w-1/2 p-4 mb-12">
          <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?w=800" class="block w-full h-auto mb-12">
          <a href="#" class="block text-2xl text-black text-center mb-6">About Us</a>
          <p class="mb-6 text-gray-600 text-center leading-relaxed text-sm">Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem.</p>
          <a href="#" class="block text-black text-center">Read more</a>
        </div>
        
        <div class="w-full md:w-1/2 p-4 mb-12">
          <img src="https://images.unsplash.com/photo-1523712999610-f77fbcfc3843?w=800" class="block w-full h-auto mb-12">
          <a href="#" class="block text-2xl text-black text-center mb-6">What's New?</a>
          <p class="mb-6 text-gray-600 text-center leading-relaxed text-sm">Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem.</p>
          <a href="#" class="block text-black text-center">Read more</a>
        </div> -->

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
  name: "About",
  data() {
    return {
      page_name: "About",
    };
  },
}
</script>

<style>

</style>
