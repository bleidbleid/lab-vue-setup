<template>
    <div>
        <h1>{{title}}</h1>
        <button @click="helloWorld2()">{{message}}</button>
    </div>
</template>


<script>
// Options api
export default {
    data() {
        return {
            // Creamos las variables que vincularemos al html
            title: 'my second component',
            message: 'Surprise 2!'
        }
    },
    methods: {
        // Crearemos las funciones que vamos a utilizar
        helloWorld2() {
            console.log('hello world')
        },
    }
}

</script>
<style scoped>
button {
  background-color: #B7F2A7;
  width: 90px;
  height: 30px;
  font-family: 'Inter', sans-serif;
}

h1 {
  font-family: 'Lora', serif;
}

div{
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
</style>