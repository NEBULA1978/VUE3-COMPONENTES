<template>
  <div>
    <ContadorImpares />
    <InputFields />
    <Usuarios />
    <TablaMultiplicar />
    <VerificadorPalindromo />
    <VerificadorPalindromo2 />
    <BuscarCoincidencia /> <!-- Corrección del nombre del componente -->
    <CadenaInvertida  />
    <Porcentaje  />
    <ContarImpares  />
  </div>
</template>

<script>
import ContadorImpares from './components/ContadorImpares.vue';
import InputFields from './components/InputFields.vue';
import Usuarios from './components/Usuarios.vue';
import TablaMultiplicar from './components/TablaMultiplicar.vue';
import VerificadorPalindromo from './components/VerificadorPalindromo.vue';
import VerificadorPalindromo2 from './components/VerificadorPalindromo2.vue';
import BuscarCoincidencia from './components/BuscarCoincidencia.vue';
import CadenaInvertida from './components/CadenaInvertida.vue';
import Porcentaje from './components/Porcentaje.vue';
import ContarImpares from './components/ContarImpares.vue';

export default {
  components: {
    ContadorImpares,
    InputFields,
    Usuarios,
    TablaMultiplicar,
    VerificadorPalindromo,
    VerificadorPalindromo2,
    BuscarCoincidencia,
    CadenaInvertida,
    Porcentaje,
    ContarImpares
  }
};
</script>
