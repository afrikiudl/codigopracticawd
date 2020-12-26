<template>
<div>
  
     <h1>Ahora estas en <strong>{{ name }}</strong></h1>  
    <b-container class="bv-example-row">
  <b-row>
    <b-col><Card /></b-col>
    <b-col><Card /></b-col>
    <b-col><Card /></b-col>
  </b-row>
</b-container>

 </div>

</template>

<script>
import Card from '../components/Card.vue' 


export default {
  props: {  
   name: {
      type: String,
      default: 'OtraPagina'
    }
  },
  components: {
        Card
      }
}
</script>