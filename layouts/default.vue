<template>
  <div>
    <Navbar/>
    <div class="min-h-screen flex flex-col font-sans">
      <section class="flex-grow p-8 text-2xl">
        <Nuxt />
      </section>
    <Footer/>
    </div>

    
  </div>
</template>
<script lang="ts">
import Vue from 'vue'
import Navbar from "~/components/layout-v2/navbar.vue";
import Footer from "~/components/layout-v2/footer.vue";


export default {
  components: {
    Navbar,
    Footer
  }
}
</script>
<style>

</style>
