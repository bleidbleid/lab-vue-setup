<template>
  <div><!-- Iteration 2
Showing data from your JavaScript inside your HTML -->
  <h1>{{const1}}</h1>
  <button @click="helloWorld()">Surprise!</button>
</div>
  
</template>
 
<script setup>
import { ref } from "vue";


const const1 = ref('my first component');


// Iteration 3
// Create a new method called helloWorld() that shows the phrase "hello world" on the console.
// Create a new button inside your component and show it on the home page.
// Call the method helloWorld() when you click on your newly created button.

const helloWorld = () => {
  console.log('hello world');
}
</script>
 
 <!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;600;700;800;900&family=Lora:ital,wght@0,400;0,500;0,600;0,700;1,400;1,500;1,600;1,700&display=swap');

button {
  background-color: #F2E0D0;
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
 