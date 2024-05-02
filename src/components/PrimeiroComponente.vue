<template>
    <div>
        <h1>Olá VUE!</h1>
        <p>Meu nome é {{ nome }} </p>
    </div>
    
</template>

<script>
    export default {
        name: 'PrimeiroComponente',
        data(){
            return {
                nome: "Thiago"
            }
        }
    }
</script>
