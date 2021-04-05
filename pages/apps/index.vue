<template>
<section class="home">
<div class="py-12 px-3">
      
      <div class="max-w-6xl mx-auto mb-6">
        
        <h2 class="mx-auto text-center text-2xl md:text-5xl max-w-3xl leading-tight text-gray-800 mb-12">{{page_name}}</h2>




      </div>



      <div class="max-w-5xl mx-auto flex flex-wrap items-start">
        
No Apps !

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
  name: "Apps",
  data() {
    return {
      page_name: "Apps",
    };
  },
}
</script>

<style>

</style>
