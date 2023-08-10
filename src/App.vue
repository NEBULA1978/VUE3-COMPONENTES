<template>
  <div>
    <ContadorImpares />
    <InputFields />
    <Usuarios />
  </div>
</template>

<script>
import ContadorImpares from './components/ContadorImpares.vue';
import InputFields from './components/InputFields.vue';
import Usuarios from './components/Usuarios.vue';

export default {
  components: {
    ContadorImpares,
    InputFields,
    Usuarios
  }
};
</script>
