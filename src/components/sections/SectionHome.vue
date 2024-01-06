<template>
  <section id="home" class="bg-blue-500 flex flex-col justify-center h-screen py-5 relative">
    <div class="container mx-auto py-4">
      <div class="flex flex-wrap">
        <div class="w-full lg:w-7/12 text-center lg:text-left self-center">
          <h1 class="text-6xl font-light mb-0 uppercase">Hi, I'm a Freelancer</h1>
          <h2 class="text-9xl font-bold uppercase mb-0 -ml-4">
            <div class="Typewriter" data-testid="typewriter-wrapper">
              <span class="Typewriter__wrapper">Developer</span>
              <span class="Typewriter__cursor">|</span>
            </div>
          </h2>
          <p class="text-xl">based in Los Angeles, USA.</p>
          <a class="btn bg-gray-800 text-white rounded-none mt-3 cursor-pointer">View My Works</a>
          <a class="btn text-gray-800 mt-3 cursor-pointer">Contact Me<span class="text-xl ml-2"><i class="far fa-arrow-alt-circle-down"></i></span></a>
        </div>
        <div class="w-full lg:w-5/12 text-center self-center mb-4 lg:mb-0">
          <div class="bg-gray-100 rounded-full inline-block p-3 shadow-lg">
            <img class="img-fluid rounded-full" src="https://picsum.photos/200/300" title="I'm Callum" alt="I'm David">
          </div>
        </div>
      </div>
    </div>
    <a class="scroll-down-arrow text-gray-800 cursor-pointer absolute bottom-4 left-1/2 transform -translate-x-1/2">
      <span class="animate-bounce"><i class="fas fa-arrow-down"></i></span>
    </a>
  </section>
</template>

<script>
export default {
  name: "SectionHome"
}
</script>

<style scoped>

</style>