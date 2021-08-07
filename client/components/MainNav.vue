<template>
  <div class="w-full flex-grow lg:flex lg:items-center lg:w-auto hidden mt-2 lg:mt-0 lg:bg-transparent text-black p-4 lg:p-0 z-20" id="nav-content">
    <ul class="list-reset lg:flex justify-end flex-1 items-center">
      <li class="mr-3">
        <nuxt-link to="/" class="inline-block py-2 px-4 text-black no-underline">Home</nuxt-link>
      </li>
      <li class="mr-3">
        <nuxt-link to="/services" class="inline-block py-2 px-4 text-black no-underline">Services</nuxt-link>
      </li>
      <li class="mr-3">
        <nuxt-link to="/contact" class="inline-block py-2 px-4 text-black no-underline">Contact</nuxt-link>
      </li>
    </ul>
    <!-- <nuxt-link to="/contact" class="mx-auto gradient lg:mx-0 bg-white text-white font-bold rounded-full mt-4 lg:mt-0 py-4 px-8 shadow opacity-75 focus:outline-none focus:shadow-outline transform transition hover:scale-105 duration-300 ease-in-out">Get a quote</nuxt-link> -->
  </div>
</template>

<style>
  .nuxt-link-exact-active {
    font-weight: bold;
  }
</style>
