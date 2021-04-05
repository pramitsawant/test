<template>
<section class="home">
<div class="py-12 px-3">
      
      <div class="max-w-6xl mx-auto mb-6">
        
        <h2 class="mx-auto text-center text-2xl md:text-5xl max-w-3xl leading-tight text-gray-800 mb-12">{{page_name}}</h2>
      </div>



      <div class="max-w-5xl mx-auto flex flex-wrap items-start">
        
        <div class="w-full md:w-1/2 p-4 mb-12" v-for="article of articles" :key="article">
          <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?w=800" class="block w-full h-auto mb-12">
          <a href="#" class="block text-2xl text-black text-center mb-6">{{article.title}}</a>
          <p class="mb-6 text-gray-600 text-center leading-relaxed text-sm">{{article.description}}</p>

          <nuxt-link class="block text-black text-center" :to="'/blogs/'+article.slug">Read More</nuxt-link>
        </div>
        


      </div>

    </div>
</section>

</template>

<script>
export default {
  components: {
  },  
  name: "Blogs",
  data() {
    return {
      page_name: "Blogs",
    };
  },
  async asyncData({ $content }) {
      const articles = await $content('articles').fetch()
      return { articles };
  }  
}
</script>

<style>

</style>
