<script setup>

import Carrusel from './components/Carrusel.vue';
import BarraNavegacion from './components/BarraNavegacion.vue';
import Descripcion from './components/Descripcion.vue';
import Piedepagina from './components/Piedepagina.vue';
</script>

<template>
  <div>
    <BarraNavegacion/>
  </div>
  <div>
    <Descripcion/>
  </div>
  <div>
    <Carrusel/>
  </div>
  <div>
    <Piedepagina/>
  </div>
  
  <HelloWorld msg="Vite + Vue" />
</template>

<style scoped>

</style>
