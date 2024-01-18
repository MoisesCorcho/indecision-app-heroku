<template>
  <h1>{{ number }}</h1>
  <button @click="incrementar">Incrementar</button>
  <button @click="decrementar">Decrementar</button>
</template>

<script>
import { ref } from 'vue'

export default {

    setup() {
        const number = ref(0)

        return {
            number,
            incrementar: () => number.value++,
            decrementar: () => number.value--
        }
    }

}
</script>

<style>

</style>