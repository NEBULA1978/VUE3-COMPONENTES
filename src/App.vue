<template>
  <div>
    <ContadorImpares />
    <InputFields />
    <Usuarios />
    <TablaMultiplicar />
    <VerificadorPalindromo /> <!-- Nuevo componente agregado -->
    <VerificadorPalindromo2 /> <!-- Nuevo componente agregado -->
    <buscarCoincidencias />
  </div>
</template>
<script>
import ContadorImpares from './components/ContadorImpares.vue';
import InputFields from './components/InputFields.vue';
import Usuarios from './components/Usuarios.vue';
import TablaMultiplicar from './components/TablaMultiplicar.vue';
import VerificadorPalindromo from './components/VerificadorPalindromo.vue';
import VerificadorPalindromo2 from './components/VerificadorPalindromo2.vue'; // Corregir el nombre del import
import BuscarCoincidencia from './components/BuscarCoincidencia.vue';
export default {
  components: {
    ContadorImpares,
    InputFields,
    Usuarios,
    TablaMultiplicar,
    VerificadorPalindromo,
    VerificadorPalindromo2, 
    BuscarCoincidencia
  }
};
</script>

