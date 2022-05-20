<template>
    <div>
        <h1>Cruzes</h1>
        <p>Meu nome é {{ nome }} e minha idade é {{ idade }} </p>
    </div>
</template>

<script>
export default {
    data() {
        return {
            nome: 'Letícia',
            idade: 26
        }
    }
}
</script>