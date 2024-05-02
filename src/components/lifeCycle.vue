<template>
    <h1>Meu nome é: {{ nome }}</h1>
</template>

<script>
// Curso de Vue 3: #07 - Entendendo os Lifecycle hooks (ciclo de vida) //
    export default {
        name: 'lifeCycle',
        data() {
            return {
                nome: "Ainda não sei"
            }
        },
        created(){
           setTimeout(() => {
            this.nome = "Matheus" 
           }, 1000);
             
        },
        mounted(){
            this.nome = "Pedro"
        }
    }
</script>