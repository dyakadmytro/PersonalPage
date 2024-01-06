<template>
  <section id="resume" class="py-12">
    <div class="container mx-auto px-4">
      <p class="text-center mb-2">
        <span class="bg-blue-500 text-white px-2">Resume</span>
      </p>
      <h2 class="text-4xl font-semibold text-center mb-5">A summary of My Resume</h2>
      <div class="flex flex-wrap gap-10 mt-5">
        <div class="w-full lg:w-1/2">
          <h2 class="text-3xl font-semibold mb-4 pb-2 border-b-2 border-blue-500">My Education</h2>
          <div class="pl-6 border-l-2 border-blue-500">
            <!-- Education Items -->
            <div class="mb-4">
              <h3 class="text-2xl">Master in Computer Engineering</h3>
              <p class="mb-2">Harvard University / 2015 - 2017</p>
              <p class="text-gray-500">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
            </div>
            <!-- More Education Items... -->
          </div>
        </div>
        <div class="w-full lg:w-1/2">
          <h2 class="text-3xl font-semibold mb-4 pb-2 border-b-2 border-blue-500">My Experience</h2>
          <div class="pl-6 border-l-2 border-blue-500">
            <!-- Experience Items -->
            <div class="mb-4">
              <h3 class="text-2xl">Sr. Front End Developer</h3>
              <p class="mb-2">Apple Inc / 2020 - current</p>
              <p class="text-gray-500">Lisque persius interesset his et, in quot quidam persequeris vim.</p>
            </div>
            <!-- More Experience Items... -->
          </div>
        </div>
      </div>
      <h2 class="text-3xl font-semibold mb-4 pb-2 mt-5 border-b-2 border-blue-500">My Skills</h2>
      <div class="flex flex-wrap gap-5">
        <!-- Skills Items -->
        <div class="w-full md:w-1/2">
          <p class="flex justify-between mb-2">Web Design <span>65%</span></p>
          <div class="w-full bg-gray-200 rounded-full h-2">
            <div class="bg-blue-500 h-2 rounded-full" style="width: 65%;"></div>
          </div>
        </div>
        <!-- More Skills Items... -->
      </div>
      <p class="text-center mt-5">
        <a class="btn border border-gray-800 rounded-none py-2 px-4" href="/path/to/resume.pdf" download="">Download CV</a>
      </p>
    </div>
  </section>

</template>

<script>
export default {
  name: "SectionResume"
}
</script>

<style scoped>

</style>