<template>
  <div>
    <PrimeiroComponente/>
    <LifeCycleVue/>
    <PessoaComponente/>
    <FormView/>
  </div>
</template>

<script>
import PrimeiroComponente from './components/PrimeiroComponente.vue'
import LifeCycleVue from './components/LifeCycle.vue';
import PessoaComponente from './components/PessoaComponente.vue';
import FormView from './components/FormView.vue'

export default {
  components: {
    PrimeiroComponente,
    LifeCycleVue,
    PessoaComponente,
    FormView,
},
  data() {
    return {};
  },
  methods: {},
};
</script>
