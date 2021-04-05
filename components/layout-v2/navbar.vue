<template>
  <nav class="px-2 py-6    mx-auto  bg-gray-900">
    <ul class="flex justify-center  px-2  ">
      <li class="md:ml-4">
        <nuxt-link :to="'/blogs'" class="text-white"> 
        <span class="xs:visible sm:visible md:invisible lg:invisible xl:invisible 2xl:invisible">B</span>
        <span class="xs:invisible sm:invisible  md:visible lg:visible xl:visible 2xl:visible">Blogs</span>
        </nuxt-link>
      </li>
      <li class="md:ml-4">
        <nuxt-link :to="'/apps'" class="text-white"> 
        <span class="xs:visible sm:visible md:invisible lg:invisible xl:invisible 2xl:invisible">A</span>
        <span class="xs:invisible sm:invisible  md:visible lg:visible xl:visible 2xl:visible">Apps</span>
        </nuxt-link>
      </li>
      <li class="md:ml-4">
        <a class="text-white" href="/">
          pramit.sawant
        </a>
      </li>
      <li class="md:ml-4">
        <nuxt-link :to="'/contact'" class="text-white"> 
        <span class="xs:visible sm:visible md:invisible lg:invisible xl:invisible 2xl:invisible">C</span>
        <span class="xs:invisible sm:invisible  md:visible lg:visible xl:visible 2xl:visible">Contact</span>
        </nuxt-link>
      </li>
      <li class="md:ml-4">
        <nuxt-link :to="'/about'" class="text-white"> 
        <span class="xs:visible sm:visible md:invisible lg:invisible xl:invisible 2xl:invisible"> A</span>
        <span class="xs:invisible sm:invisible  md:visible lg:visible xl:visible 2xl:visible">About</span>
        </nuxt-link>
      </li>
    </ul>
  </nav>
</template>