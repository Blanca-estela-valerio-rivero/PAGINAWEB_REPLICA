<script setup>

import Carrusel from './components/Carrusel.vue';
import BarraNavegacion from './components/BarraNavegacion.vue';
import Compras from './components/Compras.vue';
import ListaVideoJ from './ListaVideoJ.vue';
</script>

<template>
  <div>
    <BarraNavegacion/>
  </div>
  <div>
    <Carrusel/>
  </div>
  <div>
    <ListaVideoJ/>
  </div>
  <div>
    <Compras/>
  </div>
  
  <HelloWorld msg="Vite + Vue" />
</template>

<style scoped>

</style>
