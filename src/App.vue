<template>
  
  <PrimeiroComponente />
  <lifeCycle />
  
</template>

<script>
  import PrimeiroComponente from './components/PrimeiroComponente.vue';
  import lifeCycle from './components/lifeCycle.vue';

  export default {
    name: 'App',
    components: {
      PrimeiroComponente,
      lifeCycle
    }
  }
</script>

