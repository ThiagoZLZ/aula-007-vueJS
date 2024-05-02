<template>
    <h1>Meu nome é: {{ nome }}</h1>
</template>

<script>
// Curso de Vue 3: #07 - Entendendo os Lifecycle hooks (ciclo de vida) //
    export default {
        name: 'lifeCycle',
        data() {
            return {
                nome: "Ainda não sei teste"
            }
        },
        created(){
           setTimeout(() => {
            this.nome = "Matheus teste" 
           }, 1000);
             
        },
        mounted(){
            this.nome = "teste"
        }
    }
</script>