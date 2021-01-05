<template>
<div>
  <b-carousel
    id="carousel-fade"
    style="text-shadow: 0px 0px 2px #000"
    fade
    indicators
    img-width="1024"
    img-height="480"
  >
    <b-carousel-slide
      caption="Alumnos del grado en La Panera" 
      img-src="../assets/lapanera.jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Videojuegos y realidad virtual"
      img-src="../assets/videojuegos.jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Profesores"
      img-src="../assets/professors.jpg"
    ></b-carousel-slide>
  </b-carousel>
</div>
</template>