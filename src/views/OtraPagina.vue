<template>
  <div>

    <h1 class="pb-2">
     <icons :icon="['fas', 'star']" /> 
       (Ejemplo)
     <icons :icon="['fas', 'star']" /> 
     Ahora estas en <strong>{{ name }}</strong>
     </h1>  
      <p> Aquí se muestra el vídeo de presentación del <b-link href="http://www.graudissenydigitalitec.udl.cat/">Grado Diseño Digital y Tecnologías Creativas</b-link>.</p>

    <div>
      <b-embed
        type="iframe"
        aspect="16by9"
        src="https://www.youtube.com/embed/0sQGtf-JyUE"
        allowfullscreen
      ></b-embed>
    </div>

 </div>

</template>

<script>


export default {
  props: {  
   name: {
      type: String,
      default: 'OtraPagina'
    }
  }
}
</script>