<template>
<nav class="bg-black text-white h-16 flex items-center">
  <div class="flex items-center justify-between px-10 w-full">
    
    <!-- Left section -->
    <div class="flex items-center gap-x-6  w-8/12">
      <NuxtLink to="/" class="font-bold">Netflix</NuxtLink>
      <NuxtLink to="/">Home</NuxtLink>
      <NuxtLink to="/shows">shows</NuxtLink>
      <NuxtLink to="/movies" class="hover:text-gray-300">Movies</NuxtLink>
      <NuxtLink to="/games" class="hover:text-gray-300">Games</NuxtLink>
      <NuxtLink to="/newpopular" class="hover:text-gray-300">New&popular</NuxtLink>
      <NuxtLink to="/mylist" class="hover:text-gray-300">My List</NuxtLink>
      <NuxtLink to="/browse" class="hover:text-gray-300">Browse by languages</NuxtLink>
    </div>

    <!-- Right section -->
    <div class="flex items-center gap-x-4 w-2/12">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none"
        viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"
        class="size-5">
        <path stroke-linecap="round" stroke-linejoin="round"
          d="m21 21-5.197-5.197m0 0A7.5 7.5 0 0 0 5.196 5.196a7.5 7.5 0 0 0 10.607 10.607Z" />
      </svg>
      <NuxtLink to="/children" class="hover:text-gray-300">Children</NuxtLink>
      <div>bell</div>
      <div>icons</div>
    </div>

  </div>
</nav>








<!-- <div class="flex gap-x-6 w-full">
  <p class="w-/12">lore</p>
  <p class="">lore</p>
  <p class="">lore</p>
 <p>lore</p>
</div> -->

</template>

<script setup>

</script>



<!-- 

 <nav class="bg-gray-800 text-white px-6 py-4 flex justify-between items-center">
    <!-- Logo / Site Name -->
    <!-- <div class="text-lg font-bold">
      <NuxtLink to="/" class="hover:text-yellow-400">MySite</NuxtLink>
    </div>
<!-- 
    Links
    <div class="flex gap-6">
      <NuxtLink 
        to="/" 
        class="hover:text-yellow-400"
        :class="{ 'font-bold underline': route.path === '/' }"
      >
        Home
      </NuxtLink>
      <NuxtLink 
        to="/about" 
        class="hover:text-yellow-400"
        :class="{ 'font-bold underline': route.path === '/about' }"
      >
        About
      </NuxtLink> -->
    <!-- </div>
  </nav> -->