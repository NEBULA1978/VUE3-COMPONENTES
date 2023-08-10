<template>
  <div>
    <ContadorImpares />
    <InputFields />
  </div>
</template>

<script>
import ContadorImpares from './components/ContadorImpares.vue';
import InputFields from './components/InputFields.vue';

export default {
  components: {
    ContadorImpares,
    InputFields
  }
};
</script>
