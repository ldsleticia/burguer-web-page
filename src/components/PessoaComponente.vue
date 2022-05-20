<template>
  <div>
    <InformacoesPessoa />
  </div>
</template>

<script>
import InformacoesPessoa from "./InformacoesPessoa.vue";

export default {
  components: {
    InformacoesPessoa,
  },
  data() {
    return {
      nome: "Letícia",
    };
  },
};
</script>
