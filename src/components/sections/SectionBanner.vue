<template>
  <section>
    <div class="relative">
      <div class="absolute inset-0 bg-dark opacity-80"></div>
      <div class="relative overflow-hidden">
        <img class="absolute left-1/2 transform -translate-x-1/2 -translate-y-[200px] preserve-3d backface-hidden h-[605px] w-auto" src="https://picsum.photos/200/300" alt="Intro" loading="eager">
        <div class="relative">
          <div class="section text-center py-5">
            <div class="container mx-auto">
              <h2 class="text-4xl font-semibold text-white mb-5">Interested in working with me?</h2>
              <a class="btn bg-primary rounded-none transition duration-300 ease-in-out transform hover:scale-105">Hire Me!</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "SectionBanner"
}
</script>

<style scoped>

</style>