<template>
<div class="min-h-screen flex items-center justify-center bg-gray-100">
  <!-- This will center the grid itself -->
  <div data-aos="zoom-in">
  <div class="grid gap-8 mb-12 justify-items-center">
    <div class="bg-white/20 backdrop-blur-lg border border-white/30 shadow-lg rounded-2xl p-6 sm:p-8 text-center space-y-4 flex flex-col items-center justify-center">
      <div>
        <img src="../assets/animations/404gif.gif" alt="Logo" class="w-100 h-100 mx-auto" />
      </div>
      <h2 class="text-4xl sm:text-5xl font-bold text-[#d94c00]">Ooops!</h2>
      <p class="mt-4 text-2xl text-gray-900">Page Not Found</p>
      <p class="mt-2 text-gray-500">Sorry, the page you are looking for does not exist.</p>
      <router-link to="/"  class="inline-block bg-[#E85D04] text-white font-bold px-5 py-2 rounded-md hover:bg-[#d94c00] transition text-sm shadow-sm">
        Go back to Home
      </router-link>
    </div>
  </div>
</div>
</div>
</template>





