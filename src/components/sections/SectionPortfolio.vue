<template>
  <section id="portfolio" class="section bg-light">
    <div class="container"><p class="text-center mb-2 wow fadeInUp" style="visibility: visible;"><span
        class="bg-primary text-dark px-2">Portfolio</span></p>
      <h2 class="text-10 fw-600 text-center mb-5 wow fadeInUp" style="visibility: visible;">Some of my most recent
        projects</h2>
      <ul class="portfolio-menu nav nav-tabs fw-600 justify-content-start justify-content-md-center border-bottom-0 mb-5 wow fadeInUp"
          style="visibility: visible;">
        <li class="nav-item">
          <button class="nav-link active">All</button>
        </li>
        <li class="nav-item">
          <button class="nav-link ">Details</button>
        </li>
        <li class="nav-item">
          <button class="nav-link ">Mockups</button>
        </li>
        <li class="nav-item">
          <button class="nav-link ">Youtube Videos</button>
        </li>
        <li class="nav-item">
          <button class="nav-link ">Vimeo Videos</button>
        </li>
      </ul>
      <div class="portfolio wow fadeInUp" style="visibility: visible;">
        <div class="row portfolio-filter filter-container g-4" style="position: relative; height: 2496.85px;">
          <div class="col-sm-6 col-lg-4 filter-item DETAILED" style="position: absolute; left: 0px; top: 0px;">
            <div class="portfolio-box">
              <div class="portfolio-img"><img class="img-fluid d-block portfolio-image"
                                              src="images/projects/project-1.jpg" alt="">
                <div class="portfolio-overlay">
                  <button class="popup-ajax stretched-link border-0 p-0 "></button>
                  <div class="portfolio-overlay-details"><p class="text-primary text-8"><i
                      class="fas fa-file-alt"></i></p><h5 class="text-white text-5">Detailed Project 1</h5><span
                      class="text-light">Category</span></div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-sm-6 col-lg-4 filter-item MOCKUPS"
               style="position: absolute; left: 0px; top: 416.141px;">
            <div class="portfolio-box">
              <div class="portfolio-img"><img class="img-fluid d-block portfolio-image"
                                              src="images/projects/project-2.jpg" alt="">
                <div class="portfolio-overlay">
                  <button class="popup-ajax stretched-link border-0 p-0 "></button>
                  <div class="portfolio-overlay-details"><p class="text-primary text-8"><i
                      class="fas fa-image"></i></p><h5 class="text-white text-5">Mockups Design 1</h5><span
                      class="text-light">Category</span></div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-sm-6 col-lg-4 filter-item YOUTUBE"
               style="position: absolute; left: 0px; top: 832.282px;">
            <div class="portfolio-box">
              <div class="portfolio-img"><img class="img-fluid d-block portfolio-image"
                                              src="images/projects/project-3.jpg" alt="">
                <div class="portfolio-overlay">
                  <button class="popup-ajax stretched-link border-0 p-0 "></button>
                  <div class="portfolio-overlay-details"><p class="text-primary text-8"><i
                      class="fas fa-video"></i></p><h5 class="text-white text-5">YouTube Video</h5><span
                      class="text-light">Category</span></div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-sm-6 col-lg-4 filter-item VIMEO" style="position: absolute; left: 0px; top: 1248.42px;">
            <div class="portfolio-box">
              <div class="portfolio-img"><img class="img-fluid d-block portfolio-image"
                                              src="images/projects/project-4.jpg" alt="">
                <div class="portfolio-overlay">
                  <button class="popup-ajax stretched-link border-0 p-0 "></button>
                  <div class="portfolio-overlay-details"><p class="text-primary text-8"><i
                      class="fas fa-video"></i></p><h5 class="text-white text-5">Vimeo Video</h5><span
                      class="text-light">Category</span></div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-sm-6 col-lg-4 filter-item DETAILED"
               style="position: absolute; left: 0px; top: 1664.56px;">
            <div class="portfolio-box">
              <div class="portfolio-img"><img class="img-fluid d-block portfolio-image"
                                              src="images/projects/project-5.jpg" alt="">
                <div class="portfolio-overlay">
                  <button class="popup-ajax stretched-link border-0 p-0 "></button>
                  <div class="portfolio-overlay-details"><p class="text-primary text-8"><i
                      class="fas fa-file-alt"></i></p><h5 class="text-white text-5">Detailed Project 2</h5><span
                      class="text-light">Category</span></div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-sm-6 col-lg-4 filter-item MOCKUPS"
               style="position: absolute; left: 0px; top: 2080.7px;">
            <div class="portfolio-box">
              <div class="portfolio-img"><img class="img-fluid d-block portfolio-image"
                                              src="images/projects/project-6.jpg" alt="">
                <div class="portfolio-overlay">
                  <button class="popup-ajax stretched-link border-0 p-0 "></button>
                  <div class="portfolio-overlay-details"><p class="text-primary text-8"><i
                      class="fas fa-image"></i></p><h5 class="text-white text-5">Mockups Design 2</h5><span
                      class="text-light">Category</span></div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "SectionPortfolio"
}
</script>

<style scoped>

</style>