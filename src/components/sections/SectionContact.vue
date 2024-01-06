<template>
  <section id="contact" class="bg-primary">
    <div class="container mx-auto px-4 py-12">
      <div class="flex flex-wrap -mx-4">
        <div class="w-full lg:w-1/2 px-4 text-center lg:text-left">
          <h2 class="text-4xl font-semibold mb-5">Let's get in touch</h2>
          <p class="text-xl mb-5">I enjoy discussing new projects and design challenges. Please share as much info, as possible so we can get the most out of our first catch-up.</p>
          <h3 class="text-xl font-semibold">Living In:</h3>
          <p class="text-lg">30 Shacham street, Los Angeles, USA.</p>
          <h3 class="text-xl font-semibold">Call:</h3>
          <p class="text-lg">(+060) 444 434 444</p>
          <ul class="flex justify-center lg:justify-start mt-5 space-x-4">
            <!-- Social icons list -->
          </ul>
        </div>
        <div class="w-full lg:w-1/2 lg:ml-auto mt-5 lg:mt-0 px-4">
          <h2 class="text-4xl font-semibold text-center lg:text-left mb-5">Estimate your Project?</h2>
          <form id="contact-form" class="space-y-4">
            <div>
              <label for="name" class="block text-lg font-medium">What is Your Name:</label>
              <input id="name" name="user_name" type="text" class="form-input mt-1 block w-full" required>
            </div>
            <div>
              <label for="email" class="block text-lg font-medium">Your Email Address:</label>
              <input id="email" name="user_email" type="email" class="form-input mt-1 block w-full" required>
            </div>
            <div>
              <label for="form-message" class="block text-lg font-medium">How can I Help you?:</label>
              <textarea id="form-message" name="message" class="form-textarea mt-1 block w-full" rows="4" required></textarea>
            </div>
            <div class="text-center lg:text-left">
              <button id="submit-btn" class="btn bg-dark text-white rounded-none py-2 px-4" type="submit">Send <span class="ml-3"><i class="fas fa-arrow-right"></i></span></button>
            </div>
          </form>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "SectionContact"
}
</script>

<style scoped>

</style>