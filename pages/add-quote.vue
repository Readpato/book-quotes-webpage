<template>
  <section class="w-4/5 mx-auto h-auto p-3 mt-5">
    <h1 class="text-center text-xl">Add a quote</h1>
    <form class="flex flex-col space-y-2 w-full md:max-w-lg mx-auto">
      <div class="flex flex-col space-y-1">
        <label for="author-name">Author's Name</label>
        <input
          type="text"
          id="author-name"
          class="border-2 border-red-400 rounded p-1 focus:outline-none focus:ring-2 focus:ring-red-500"
        />
      </div>
      <div class="flex flex-col space-y-1">
        <label for="book-name">Book Name</label>
        <input
          type="text"
          id="book-name"
          class="border-2 border-red-400 rounded p-1 focus:outline-none focus:ring-2 focus:ring-red-500"
        />
      </div>
      <div class="flex flex-col space-y-1">
        <label for="quote-text">Quote</label>
        <textarea
          id="book-name"
          class="border-2 border-red-400 rounded p-1 focus:outline-none focus:ring-2 focus:ring-red-500"
        />
      </div>
      <button
        @click.prevent=""
        class="border-2 border-cyan-400 w-40 p-3 mx-auto rounded bg-cyan-400 text-white text-base hover:border-cyan-300"
      >
        Submit Quote
      </button>
    </form>
  </section>
</template>
