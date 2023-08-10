<template>
  <div>
    <!-- Ponemos nombre de funcion -->
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
    <InvertirNumero  />
    <ElementosComunes  />
    <Repeticiones  />
    <BuscarLetraMasRepetida  />
    <ContarVocales  />
  </div>
</template>

<script>
// Ponemos nombre Componente
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
import InvertirNumero from './components/InvertirNumero.vue';
import ElementosComunes from './components/ElementosComunes.vue';
import Repeticiones from './components/Repeticiones.vue';
import BuscarLetraMasRepetida from './components/BuscarLetraMasRepetida.vue';
import ContarVocales from './components/ContarVocales.vue';

export default {
  components: {
    // Ponemos nombre de archivo componente del template
    ContadorImpares,
    InputFields,
    Usuarios,
    TablaMultiplicar,
    VerificadorPalindromo,
    VerificadorPalindromo2,
    BuscarCoincidencia,
    CadenaInvertida,
    Porcentaje,
    ContarImpares,
    InvertirNumero,
    ElementosComunes,
    Repeticiones,
    BuscarLetraMasRepetida,
    ContarVocales
  }
};
</script>
