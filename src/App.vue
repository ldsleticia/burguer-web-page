<template>
  <div>
    <PrimeiroComponente/>
    <LifeCycleVue/>
  </div>
</template>

<script>
import PrimeiroComponente from './components/PrimeiroComponente.vue'
import LifeCycleVue from './components/LifeCycle.vue';

export default {
  components: {
    PrimeiroComponente,
    LifeCycleVue,
},
  data() {
    return {};
  },
  methods: {},
};
</script>
