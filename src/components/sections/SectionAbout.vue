<template>
  <section id="about" class="py-12">
    <div class="container mx-auto px-4">
      <p class="text-center mb-2">
        <span class="bg-primary text-white px-2">About Me</span>
      </p>
      <h2 class="text-4xl font-semibold text-center mb-5">Know Me More</h2>
      <div class="flex flex-wrap -mx-4">
        <div class="w-full lg:w-2/3 px-4 text-center lg:text-left">
          <h2 class="text-3xl font-light mb-3">Hi, I'm <span class="font-bold border-b-4 border-primary">Callum Smith</span></h2>
          <p class="text-xl">I'm a designer & developer with a passion for web design. I enjoy developing simple, clean, and slick websites that provide real value to the end user. Thousands of clients have procured exceptional results while working with me. Delivering work within time and budget which meets client’s requirements is our motto.</p>
        </div>
        <div class="w-full lg:w-1/3 mt-4 lg:mt-0 px-4">
          <div class="featured-box text-center">
            <div class="text-6xl font-semibold bg-primary rounded-full w-16 h-16 flex items-center justify-center mx-auto">22</div>
            <h3 class="text-3xl mt-2">Years of <span class="font-bold">Experience</span></h3>
          </div>
        </div>
      </div>
      <div class="flex flex-wrap text-center mt-4">
        <div class="w-1/2 lg:w-1/4 px-4">
          <p class="text-gray-600 font-medium mb-0">Name:</p>
          <p class="text-xl font-semibold mb-0">Callum Smith</p>
        </div>
        <div class="w-1/2 lg:w-1/4 px-4">
          <p class="text-gray-600 font-medium mb-0">Email:</p>
          <p class="text-xl font-semibold mb-0"><a class="text-current" href="mailto:chat@callum.com">chat@callum.com</a></p>
        </div>
        <div class="w-1/2 lg:w-1/4 px-4">
          <p class="text-gray-600 font-medium mb-0">Date of birth:</p>
          <p class="text-xl font-semibold mb-0">11 November, 1987</p>
        </div>
        <div class="w-1/2 lg:w-1/4 px-4">
          <p class="text-gray-600 font-medium mb-0">From:</p>
          <p class="text-xl font-semibold mb-0">Los Angeles, USA.</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "SectionAbout"
}
</script>

<style scoped>

</style>