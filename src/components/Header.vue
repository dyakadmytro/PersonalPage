<template>
  <header id="header" class="sticky-top">
    <nav
        class="primary-menu navbar navbar-expand-none navbar-overlay  bg-transparent border-bottom-0 text-5 fw-600  navbar-overlay-dark">
      <div class="container"><a class="logo" title="Callum" style="cursor: pointer;"><img src="../assets/images/logo.png"
                                                                                          alt="Callum"></a>
        <div class="text-3 ms-auto me-2 "><span class="text-4 me-2"><i class="fas fa-phone"></i></span>(060) 444 434
          444
        </div>
        <button class="navbar-toggler collapsed " type="button"><span></span><span></span><span></span></button>
        <div id="header-nav" class="collapse navbar-collapse ">
          <div class="d-flex flex-column h-100 align-items-center justify-content-center">
            <ul class="navbar-nav">
              <li class="nav-item"><a class="nav-link  active" style="cursor: pointer;">Home</a></li>
              <li class="nav-item"><a class="nav-link " style="cursor: pointer;">About Me</a></li>
              <li class="nav-item"><a class="nav-link " style="cursor: pointer;">What I Do</a></li>
              <li class="nav-item"><a class="nav-link " style="cursor: pointer;">Resume</a></li>
              <li class="nav-item"><a class="nav-link " style="cursor: pointer;">Portfolio</a></li>
              <li class="nav-item"><a class="nav-link " style="cursor: pointer;">FAQ</a></li>
              <li class="nav-item"><a class="nav-link " style="cursor: pointer;">Client Speak</a></li>
              <li class="nav-item"><a class="nav-link " style="cursor: pointer;">Contact Me</a></li>
            </ul>
            <ul class="social-icons social-icons-light social-icons-lg social-icons-light d-inline-flex mt-4">
              <li class="social-icons-twitter"><a href="https://twitter.com/harnishdesign/" target="_blank"
                                                  rel="noopener noreferrer"><i class="fab fa-twitter"></i></a></li>
              <li class="social-icons-facebook"><a href="http://www.facebook.com/harnishdesign/" target="_blank"
                                                   rel="noopener noreferrer"><i class="fab fa-facebook"></i></a>
              </li>
              <li class="social-icons-instagram"><a href="http://www.instagram.com/" target="_blank"
                                                    rel="noopener noreferrer"><i class="fab fa-instagram"></i></a>
              </li>
              <li class="social-icons-linkedin"><a href="http://www.linkedin.com/" target="_blank"
                                                   rel="noopener noreferrer"><i class="fab fa-linkedin-in"></i></a>
              </li>
              <li class="social-icons-dribbble"><a href="http://www.dribbble.com/harnishdesign/" target="_blank"
                                                   rel="noopener noreferrer"><i class="fab fa-dribbble"></i></a>
              </li>
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