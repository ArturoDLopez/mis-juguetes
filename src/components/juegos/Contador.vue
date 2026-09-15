<script setup>
import { ref } from 'vue'

const contador = ref(0)

</script>

<template>
    <br>
    Este es un botón que muestra cuantas veces ha sido clickeado
    <button @click="contador++">
        Conteo: {{ contador }}
    </button>

</template>