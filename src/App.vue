<template>
  <div>
    <PrimeiroComponente/>
    <LifeCycleVue/>
    <PessoaComponente/>
  </div>
</template>

<script>
import PrimeiroComponente from './components/PrimeiroComponente.vue'
import LifeCycleVue from './components/LifeCycle.vue';
import PessoaComponente from './components/PessoaComponente.vue';

export default {
  components: {
    PrimeiroComponente,
    LifeCycleVue,
    PessoaComponente,
},
  data() {
    return {};
  },
  methods: {},
};
</script>
