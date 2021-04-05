<template>
<div class="w-full h-screen relative text-white">
      <img src="https://images.unsplash.com/photo-1438109491414-7198515b166b?w=1800" class="absolute top-0 left-0 w-full h-full object-cover">

      <header class="z-10  relative mx-auto max-w-6xl px-6 py-8 md:flex xl:flex justify-between items-center">
        <div class="flex justify-center">
        <a href="#" class="text-xl text-center tracking-wider">pramit.sawant</a>
        </div>
        <ul class="flex p-2 lg:p-6 items-center uppercase text-gray-500 bg-white bg-opacity-10 rounded">

          <li class="ml-3 md:ml-4 lg:ml-6 text-sm md:text-md lg:text-md ">
           
            <nuxt-link :to="'/'" class="text-white"> Home</nuxt-link>
          </li>
          <li class="ml-3 md:ml-4 lg:ml-6 text-sm md:text-md lg:text-md ">
            <a href="#" class="text-white">Porfolio</a>
          </li>
          <li class="ml-3 md:ml-4 lg:ml-6 text-sm md:text-md lg:text-md">
            
            <nuxt-link :to="'/apps'" class="text-white"> Apps</nuxt-link>
          </li>          
          <li class="ml-3 md:ml-4 lg:ml-6 text-sm md:text-md lg:text-md">
            <a href="#" class="text-white">Blogs</a>
          </li>
          <li class="ml-3 md:ml-4 lg:ml-6  text-sm md:text-md lg:text-md">
            <a href="#" class="text-white">Contact</a>
          </li>

        </ul>


      </header>

      <div class="absolute top-0 left-0 w-full h-full flex justify-center items-center text-center px-12">
        <div>
          <h1 class="text-3xl md:text-6xl leading-tight mb-16">Live, Love, </h1>
          <a href="#" class="border border-white py-4 px-8 hover:bg-white hover:text-black">Get started</a>
        </div>
      </div>

    </div>
</template>