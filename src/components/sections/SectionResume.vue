<template>
  <section id="resume" class="h-dvh border-b-4">
    <div class="h-full mx-auto m-5 md:m-20">
      <p class="text-center mb-20 chapter">
        <span class="">Resume</span>
      </p>
      <h2 class="text-6xl font-semibold text-center mb-40">A summary of My Resume <span class="text-amber-400 p-2 text-7xl">✓</span></h2>
      <div class="grid grid-cols-2 gap-10 mb-16">
        <div>
          <h2 class="text-3xl font-semibold mb-5">My Education</h2>
          <div class="border-l-2 border-amber-400 pl-16 mt-16">
            <div class="py-5 border-b-2 border-slate-200">
              <h3 class="text-2xl py-5">Master in Computer Engineering</h3>
              <p class="mb-2">Harvard University / 2015 - 2017</p>
              <p class="text-gray-500">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
            </div>
            <div class="py-5 border-b-2 border-slate-200">
              <h3 class="text-2xl">Master in Computer Engineering</h3>
              <p class="mb-2">Harvard University / 2015 - 2017</p>
              <p class="text-gray-500">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
            </div>
            <div class="py-5">
              <h3 class="text-2xl">Master in Computer Engineering</h3>
              <p class="mb-2">Harvard University / 2015 - 2017</p>
              <p class="text-gray-500">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
            </div>
          </div>
        </div>
        <div>
          <h2 class="text-3xl font-semibold mb-5">My Experience</h2>
          <div class="border-l-2 border-amber-400 pl-16 mt-16">
            <div class="pl-6">
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
      </div>
      <h2 class="text-3xl font-semibold mb-4 ">My Skills</h2>
      <div class="grid grid-cols-2 gap-10 mb-16">
        <div>
          <div class="py-5">
            <p class="flex justify-between mb-2">Web Design <span>65%</span></p>
            <div class="w-full bg-gray-200 rounded-full h-2">
              <div class="bg-blue-500 h-2 rounded-full" style="width: 65%;"></div>
            </div>
          </div>
          <div class="py-5">
            <p class="flex justify-between mb-2">Web Design <span>65%</span></p>
            <div class="w-full bg-gray-200 rounded-full h-2">
              <div class="bg-blue-500 h-2 rounded-full" style="width: 65%;"></div>
            </div>
          </div>
          <div class="py-5">
            <p class="flex justify-between mb-2">Web Design <span>65%</span></p>
            <div class="w-full bg-gray-200 rounded-full h-2">
              <div class="bg-blue-500 h-2 rounded-full" style="width: 65%;"></div>
            </div>
          </div>
        </div>
        <div>
          <p class="flex justify-between mb-2">Web Design <span>65%</span></p>
          <div class="w-full bg-gray-200 rounded-full h-2">
            <div class="bg-blue-500 h-2 rounded-full" style="width: 65%;"></div>
          </div>
        </div>
      </div>
      <p class="text-center mt-5">
        <a class="btn border border-gray-800 bg-amber-400 font-semibold rounded-none py-2 px-4" href="/path/to/resume.pdf" download="">Download CV</a>
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
#resume {
  height: max-content;
  padding-bottom: 100px;
}
</style>