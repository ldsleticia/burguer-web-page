<template>
  <div>
    <input type="text" v-model="input_name" placeholder="digite seu nome"/>
    <input type="text" v-model="input_age" placeholder="digite sua idade">
    <input type="submit" value="Enviar" @click="submitForm">

    <p>Seu nome é {{ name }} e você tem {{ age }} anos</p>
  </div>
</template>

<script>


export default {
  data() {
    return {
      name: '',
      age: '',
      input_name: '',
    }
  },
  methods: {
    submitForm(e){
      e.preventDefault();
      console.log(this.input_name)
      this.name = this.input_name
      this.age = this.input_age
    }
  }
}
</script>
