<template>
  <nav
    class="w-full h-14 bg-red-500 flex justify-between items-center p-3 text-white"
  >
    <h1 class="text-white text-xl">Book Quotes</h1>
    <ul class="flex space-x-3">
      <li
        class="cursor-pointer hover:outline hover:outline-red-400 p-1 rounded"
      >
        <NuxtLink>Quotes</NuxtLink>
      </li>
      <li
        class="cursor-pointer hover:outline hover:outline-red-400 p-1 rounded"
      >
        <NuxtLink>About</NuxtLink>
      </li>
    </ul>
  </nav>
</template>
