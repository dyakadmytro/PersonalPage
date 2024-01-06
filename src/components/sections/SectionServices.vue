<template>
  <section id="services" class="bg-gray-100 py-12">
    <div class="container mx-auto px-4">
      <p class="text-center mb-2">
        <span class="bg-blue-500 text-white px-2">What I Do?</span>
      </p>
      <h2 class="text-4xl font-semibold text-center mb-5">How I can help your next project</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-5 mt-5">
        <!-- Service Item 1 -->
        <div class="text-center px-4">
          <div class="text-blue-500 text-5xl mb-3"><i class="fas fa-palette"></i></div>
          <h3 class="text-2xl font-semibold mb-3">Graphic Design</h3>
          <p class="text-gray-500">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
        </div>
        <!-- Service Item 2 -->
        <div class="text-center px-4">
          <div class="text-blue-500 text-5xl mb-3"><i class="fas fa-desktop"></i></div>
          <h3 class="text-2xl font-semibold mb-3">Web Design</h3>
          <p class="text-gray-500">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
        </div>
        <!-- Additional Service Items... -->
      </div>
    </div>
  </section>

</template>

<script>
export default {
  name: "SectionServices"
}
</script>

<style scoped>

</style>