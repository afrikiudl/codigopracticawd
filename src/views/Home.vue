<template>
<div id="home">
     <h1>Página de ejemplo del Grado Diseño Digital y Tecnologías Creativas</h1>  

      <p>Esta web es un <strong>ejemplo</strong> de la asignatura de Web Dinámica del   
      <b-link href="http://www.graudissenydigitalitec.udl.cat/">Grado Diseño Digital y Tecnologías Creativas</b-link> 
      de la 
      <b-link href="http://www.udl.cat/">Universitat de Lleida</b-link>.
    </p>
    <p>Consulta
      <b-link href="https://www.instagram.com/creartive.lleida/">Instagram</b-link>
      para ver más información del grupo de alumnos.
    </p>

     <Diapos/>
 </div>
</template>

<script>
import Diapos from '../components/Diapos.vue' 

export default {
   name: 'Home',
   components: {
        Diapos
  }
}
</script>