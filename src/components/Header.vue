<template>
  <header id="header" :class="[ headerColor() , 'sticky top-0 h-20 z-30']">
    <nav class="w-full font-semibold text-white ">
      <div class="flex w-full flex-wrap items-center justify-between px-3 text-slate-100">
        <a class="logo" title="Callum" style="cursor: pointer;">
          <img class="w-20" src="../assets/images/logo.png" alt="DykaDmytro">
        </a>
        <div class="ml-5 flex w-[25%] items-center justify-between">
          <div class="text-xl font-bold">
          <span class="text-lg me-2">
            <i class="fas fa-phone"></i>
          </span>
            (060) 444 434 444
          </div>
          <div id="nav-burger" v-on:click="toggleBurger" :class="burgerActive? 'open z-50': ''">
            <span></span>
            <span></span>
            <span></span>
          </div>
        </div>
      </div>
      <div id="header-nav" :class="[burgerActive? 'z-40 absolute bg-zinc-900 w-full opacity-90 top-0' : 'hidden', 'flex items-center justify-center h-screen']">
        <div class="flex flex-col h-full items-center justify-center leading-10 text-4xl font-bold">
          <ul class="navbar-nav text-center">
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
    </nav>
  </header>

</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      burgerActive: false,
      scrollY: 0
    }
  },
  mounted() {
    window.addEventListener('scroll', this.updateScroll);
  },
  unmounted() {
    window.removeEventListener('scroll', this.updateScroll);
  },
  computed: {
  },
  methods: {
    headerColor() {
      return this.scrollY > 0 ? 'bg-zinc-800 transition ease-out duration-500' : 'bg-amber-400 transition ease-out duration-500';
    },
    toggleBurger() {
      this.burgerActive = !this.burgerActive
    },
    updateScroll() {
      this.scrollY = window.scrollY;
    }
  }
}
</script>

<style scoped>
header {
  padding-right: 0!important;
}
#nav-burger span {
  display: block;
  position: absolute;
  height: 9px;
  width: 100%;
  background: #f1f5f9;
  border-radius: 9px;
  opacity: 1;
  left: 0;
  -webkit-transform: rotate(0deg);
  -moz-transform: rotate(0deg);
  -o-transform: rotate(0deg);
  transform: rotate(0deg);
  -webkit-transition: .25s ease-in-out;
  -moz-transition: .25s ease-in-out;
  -o-transition: .25s ease-in-out;
  transition: .25s ease-in-out;
}

#nav-burger {
  width: 60px;
  height: 45px;
  position: relative;
  margin: 5px;
  -webkit-transform: rotate(0deg);
  -moz-transform: rotate(0deg);
  -o-transform: rotate(0deg);
  transform: rotate(0deg);
  -webkit-transition: .5s ease-in-out;
  -moz-transition: .5s ease-in-out;
  -o-transition: .5s ease-in-out;
  transition: .5s ease-in-out;
  cursor: pointer;
}

#nav-burger span:nth-child(1) {
  top: 0px;
  -webkit-transform-origin: left center;
  -moz-transform-origin: left center;
  -o-transform-origin: left center;
  transform-origin: left center;
}

#nav-burger span:nth-child(2) {
  top: 18px;
  -webkit-transform-origin: left center;
  -moz-transform-origin: left center;
  -o-transform-origin: left center;
  transform-origin: left center;
}

#nav-burger span:nth-child(3) {
  top: 36px;
  -webkit-transform-origin: left center;
  -moz-transform-origin: left center;
  -o-transform-origin: left center;
  transform-origin: left center;
}

#nav-burger.open span:nth-child(1) {
  -webkit-transform: rotate(45deg);
  -moz-transform: rotate(45deg);
  -o-transform: rotate(45deg);
  transform: rotate(45deg);
  top: -3px;
  left: 8px;
}

#nav-burger.open span:nth-child(2) {
  width: 0%;
  opacity: 0;
}

#nav-burger.open span:nth-child(3) {
  -webkit-transform: rotate(-45deg);
  -moz-transform: rotate(-45deg);
  -o-transform: rotate(-45deg);
  transform: rotate(-45deg);
  top: 39px;
  left: 8px;
}
</style>