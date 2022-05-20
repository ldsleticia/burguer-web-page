<template>
  <div>
    <h1>Meu nome é: {{ nome }}</h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      nome: "ainda não sei",
    };
  },
  created() {
    setTimeout(() => {
      this.nome = "Matheus";
    }, 1000);
  },
  mounted() {
    setTimeout(() => {
      this.nome = 'Janaina'
    }, 2000)
  },
};
</script>
