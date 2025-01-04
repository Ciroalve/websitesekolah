<template>
  <div class="container-fluid">
      <div class="row">
          <div class="col-lg-12">
              <h5 style="background-color: black;" class="text-white text-center rounded-3 p-2 m-3">
                  Galeri foto  <b>SMKN 4 TASIKMALAYA</b>
              </h5>
          </div>
          <section class="gallery text-center">
              <div class="gallery-item">
                  <img src="/assets/img/sr.jpg" alt="SR" class="gallery-img" />
                  <p class="gallery-caption">safety riding</p>
              </div>
              <div class="gallery-item">
                  <img src="/assets/img/job per.jpg" alt="jobper" class="gallery-img" />
                  <p class="gallery-caption">job falr</p>
              </div>
              <div class="gallery-item">
                  <img src="/assets/img/binsik.jpg" alt="binsik" class="gallery-img" />
                  <p class="gallery-caption">penbinaan fisik</p>
              </div>
              <div class="gallery-item">
                  <img src="/assets/img/honda.jpg" alt="honda" class="gallery-img" />
                  <p class="gallery-caption">kerjasama dengan honda</p>
              </div>
          </section>
      </div>
  </div>
</template>

<style scoped>
.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
  gap: 20px;
  margin: 20px 0;
}

.gallery-item {
  background-color: #f9f9f9;
  border: 1px solid #ddd;
  border-radius: 8px;
  padding: 10px;
  transition: transform 0.3s;
}

.gallery-item:hover {
  transform: scale(1.05);
}

.gallery-item img {
  max-width: 200px;
  border-radius: 8px;
}

.gallery-caption {
  color: #000000;
  margin-top: 20px;
}
</style>