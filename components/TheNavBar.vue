<template>
  <nav
    class="w-full h-16 bg-red-500 flex justify-between items-center p-3 text-white"
  >
    <h1 class="text-white text-base md:text-xl">Book Quotes</h1>
    <ul class="flex space-x-3 text-sm md:text-base">
      <li
        class="cursor-pointew-screenr hover:outline hover:outline-red-400 p-1 rounded"
      >
        <NuxtLink to="/">Quotes</NuxtLink>
      </li>
      <li
        class="cursor-pointer hover:outline hover:outline-red-400 p-1 rounded"
      >
        <NuxtLink to="/add-quote">Add</NuxtLink>
      </li>
      <li
        class="cursor-pointer hover:outline hover:outline-red-400 p-1 rounded"
      >
        <NuxtLink to="/about">About</NuxtLink>
      </li>
    </ul>
  </nav>
</template>
