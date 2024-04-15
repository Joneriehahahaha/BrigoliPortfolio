<template>
  <div class="flex flex-col items-center min-h-screen">
    <div class="text-center">
      <div class="mx-auto mb-4 mt-20 md:mt-32 h-48 w-48 md:h-64 md:w-64 overflow-hidden rounded-full bg-gradient-to-tr from-orange-500 to-purple-700">
        <img src="/images/brigoli.png" alt="" class="w-full h-full object-cover" />
      </div>
      <h1 class="max-w-screen-sm text-4xl font-extrabold text-black mb-8">
         <br />
         <span class="text-transparent bg-clip-text bg-gradient-to-tr from-orange-500 to-purple-700"> </span>
      </h1>
      <p class="mx-auto mb-16 text-lg font-lg font-semibold text-black max-w-lg">Hello, I`m Klien Brigoli, and I`m a third-year college student pursuing a Bachelor of Science in Information Technology
      </p>
      
      <p class="mx-auto mb-16 text-lg font-lg font-semibold text-black max-w-lg">At Cordova Public College, I am constantly learning and honing my skills through hands-on projects, coursework, and collaboration with peers and instructors. I believe in the importance of staying updated with the latest advancements in technology and actively seek opportunities to expand my knowledge and expertise.
      </p>
      <div class="text-center">
        <button class="text-gray-800 inline-block px-8 py-4 mr-4 bg-blue-400 rounded-full font-semibold text-lg">Get In Touch</button>
        <button class="text-black inline-block px-8 py-4 bg-transparent border-2 border-black rounded-full font-semibold text-lg">Download CV</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  // Component logic
};
</script>

<style scoped>
@media (min-width: 640px) {
  .h-24 {
    height: 6rem; /* Adjust the height for smaller screens */
  }
  .w-24 {
    width: 6rem; /* Adjust the width for smaller screens */
  }
}
</style>
