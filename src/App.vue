<template>
  <CounterCompositionApi/>
  <CounterVue/>
  <!-- <Indecision /> -->
</template>

<script>
import Indecision from '@/components/Indecision.vue'
import CounterVue from '@/components/CounterTest.vue'
import CounterCompositionApi from '@/components/CounterCompositionApi.vue'

export default {
  name: 'App',
  components: {
    CounterCompositionApi,
    CounterVue,
    Indecision
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
