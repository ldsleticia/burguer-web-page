<template>
  <div>
    <InputText />
    <SubmitButton/>
  </div>
</template>

<script>
import InputText from "./InputText.vue";
import SubmitButton from './SubmitButton.vue'

export default {
  components: {
    InputText,
    SubmitButton,
  },
};
</script>
