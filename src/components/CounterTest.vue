<template>
  <h1>{{ Counter }}</h1>
  <button @click="increment">Incrementar</button>
  <button @click="decrement">Decrementar</button>
</template>

<script>
export default {
    data() {
        return {
            Counter: 0
        }
    },
    methods: {
        increment() {
            return this.Counter++
        },
        decrement() {
            return this.Counter--
        }
    }
}
</script>

<style>

</style>