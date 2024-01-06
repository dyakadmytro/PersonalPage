<template>
  <header id="header" class="sticky top-0">
    <nav class="primary-menu navbar navbar-expand-none bg-transparent border-b-0 text-lg font-semibold text-white">
      <div class="container mx-auto">
        <a class="logo" title="Callum" style="cursor: pointer;">
          <img src="../assets/images/logo.png" alt="Callum">
        </a>
        <div class="text-base ms-auto me-2">
        <span class="text-lg me-2">
          <i class="fas fa-phone"></i>
        </span>
          (060) 444 434 444
        </div>
        <button class="navbar-toggler collapsed" type="button">
          <span></span>
          <span></span>
          <span></span>
        </button>
        <div id="header-nav" class="collapse navbar-collapse">
          <div class="flex flex-col h-full items-center justify-center">
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link active" style="cursor: pointer;">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" style="cursor: pointer;">About Me</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" style="cursor: pointer;">What I Do</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" style="cursor: pointer;">Resume</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" style="cursor: pointer;">Portfolio</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" style="cursor: pointer;">FAQ</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" style="cursor: pointer;">Client Speak</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" style="cursor: pointer;">Contact Me</a>
              </li>
            </ul>
            <ul class="social-icons flex mt-4">
              <!-- Social icons list -->
            </ul>
          </div>
        </div>
      </div>
    </nav>
  </header>

</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>

</style>