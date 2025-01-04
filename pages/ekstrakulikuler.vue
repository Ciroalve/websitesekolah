<template>
    <div class="container-fluid">
        <div class="row">
            <div class="col-lg-12">
                <h5 style="background-color: black;" class="text-white text-center rounded-3 p-2 m-3">
                    Ekstrakulikuler <b>SMKN 4 TASIKMALAYA</b>
                </h5>
            </div>
            <section class="gallery text-center">
                <div class="gallery-item">
                    <img src="/assets/img/futsal.png" alt="Lomba Futsal" class="gallery-image" />
                    <p class="gallery-caption">Futsal</p>
                </div>
                <div class="gallery-item">
                    <img src="/assets/img/perisai.jpg" alt="Lomba perisai" class="gallery-image" />
                    <p class="gallery-caption">perisai</p>
                </div>
                <div class="gallery-item">
                    <img src="/assets/img/plh.jpg" alt="lomba plh" class="gallery-image" />
                    <p class="gallery-caption">plh</p>
                </div>
                <div class="gallery-item">
                    <img src="/assets/img/pmr.jpg" alt="lomba pmr" class="gallery-image" />
                    <p class="gallery-caption">pmr</p>
                </div>
                <div class="gallery-item">
                    <img src="/assets/img/pramuka.jpg" alt="lomba pramuka" class="gallery-image" />
                    <p class="gallery-caption">Pramuka</p>
                </div>
                <div class="gallery-item">
                    <img src="/assets/img/pks.jpg" alt="lomba pks" class="gallery-image" />
                    <p class="gallery-caption">Pks</p>
                </div>
                <div class="gallery-item">
                    <img src="/assets/img/voli.jpeg" alt="lomba voli" class="gallery-image" />
                    <p class="gallery-caption">voli</p>
                </div>
                <div class="gallery-item">
                    <img src="/assets/img/basket.jpg" alt="lomba basket" class="gallery-image" />
                    <p class="gallery-caption">basket</p>
                </div>
                <div class="gallery-item">
                    <img src="/assets/img/bultang.jpg" alt="" class="gallery-image" />
                    <p class="gallery-caption">bultang</p>
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
  
  .gallery-image {
    max-width: 100%;
    
  }
  
  .gallery-caption {
    color: #000000;
    margin-top: 20px;
  }
  </style>