<template>
  <main class="columns is-gapless is-multiline">
    <div class="column is-one-quarter">
      <BarraLateral />
    </div>
    <div class="column is-three-quarter">
      <FormTarefa />
    </div>
  </main>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import BarraLateral from './components/BarraLateral.vue';
import FormTarefa from './components/FormTarefa.vue';
export default defineComponent({
  name: 'App',
  components: {
    BarraLateral,
    FormTarefa
  }
});
</script>

<style>

</style>
