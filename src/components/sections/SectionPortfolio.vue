<template>
  <section id="portfolio" class="bg-gray-100">
    <div class="container mx-auto px-4 py-12">
      <p class="text-center mb-2">
        <span class="bg-blue-500 text-white px-2">Portfolio</span>
      </p>
      <h2 class="text-5xl font-semibold text-center mb-5">Some of my most recent projects</h2>
      <div class="flex flex-wrap justify-center mb-5">
        <button class="bg-gray-200 text-black px-4 py-2 m-1 rounded focus:outline-none focus:bg-gray-300">All</button>
        <button class="bg-gray-200 text-black px-4 py-2 m-1 rounded focus:outline-none focus:bg-gray-300">Details</button>
        <button class="bg-gray-200 text-black px-4 py-2 m-1 rounded focus:outline-none focus:bg-gray-300">Mockups</button>
        <button class="bg-gray-200 text-black px-4 py-2 m-1 rounded focus:outline-none focus:bg-gray-300">Youtube Videos</button>
        <button class="bg-gray-200 text-black px-4 py-2 m-1 rounded focus:outline-none focus:bg-gray-300">Vimeo Videos</button>
      </div>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
        <div class="group">
          <div class="relative">
            <img class="w-full h-auto" src="https://picsum.photos/200/300" alt="">
            <div class="absolute inset-0 bg-black bg-opacity-50 opacity-0 group-hover:opacity-100 flex justify-center items-center transition duration-300 ease-in-out">
              <div class="text-center">
                <p class="text-blue-500 text-4xl"><i class="fas fa-file-alt"></i></p>
                <h5 class="text-white text-xl">Detailed Project 1</h5>
                <span class="text-gray-300">Category</span>
              </div>
            </div>
          </div>
        </div>
        <div class="group">
          <div class="relative">
            <img class="w-full h-auto" src="https://picsum.photos/200/300" alt="">
            <div class="absolute inset-0 bg-black bg-opacity-50 opacity-0 group-hover:opacity-100 flex justify-center items-center transition duration-300 ease-in-out">
              <div class="text-center">
                <p class="text-blue-500 text-4xl"><i class="fas fa-image"></i></p>
                <h5 class="text-white text-xl">Mockups Design 1</h5>
                <span class="text-gray-300">Category</span>
              </div>
            </div>
          </div>
        </div>
        <div class="group">
          <div class="relative">
            <img class="w-full h-auto" src="https://picsum.photos/200/300" alt="">
            <div class="absolute inset-0 bg-black bg-opacity-50 opacity-0 group-hover:opacity-100 flex justify-center items-center transition duration-300 ease-in-out">
              <div class="text-center">
                <p class="text-blue-500 text-4xl"><i class="fas fa-video"></i></p>
                <h5 class="text-white text-xl">YouTube Video</h5>
                <span class="text-gray-300">Category</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "SectionPortfolio"
}
</script>

<style scoped>

</style>