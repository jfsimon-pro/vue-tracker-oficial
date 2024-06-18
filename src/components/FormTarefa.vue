<template>
    <div class="box">
        <div class="columns is-8" role="form" aria-label="Formulário para criação de uma nova tarefa">
            <input type="text" class="input" placeholder="Qual tarefa você deseja inciiar?">
        </div>
        <div class="column">
            <TemporizadorNovo />
        </div>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import TemporizadorNovo from "./TemporizadorNovo.vue"
export default defineComponent({
    name: 'FormTarefa',
    components:{
        TemporizadorNovo
    }
})
</script>