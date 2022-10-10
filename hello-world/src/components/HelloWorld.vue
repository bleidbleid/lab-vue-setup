<template>
 <h1>{{caca}}</h1>
 <button>
  
</button>
</template>

<script setup>
import { ref } from "vue";
const caca = ref('andrew');


// This challenge is a bit more advanced; but it will show you how easy it is to create and trigger functions (or methods, as they're called in Vue) when you're working with a JavaScript method.
// Here's what you need to do:

// Create a new method called helloWorld() that shows the phrase "hello world" on the console.
// Create a new button inside your component and show it on the home page.
// Call the method helloWorld() when you click on your newly created button.

const helloWorld = () => {
    console.log('hello world');
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
