<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <div id="app">
    <div>
        <header class="bg-green-600 p-20">
            <h1 class="text-white text-4xl text-center">Header</h1>
            <h2 class="text-white text-xl text-center">Scroll down to see the effect</h2>
        </header>
        <header class="bg-black-600">
            <nav class="sticky z-9999 w-1/3 top-6 bg-blue-600 p-5 drop-shadow shadow-blue-600">
              <h1 class="text-white text-4xl text-center">Sticky Nav Bar</h1>
            </nav>
            <h1 class="text-white text-4xl text-center">Header</h1>
            <h2 class="text-white text-xl text-center">Scroll down to see the effect</h2>
            <header class="bg-red-600 p-20">
                <h1 class="text-white text-4xl text-center">Header</h1>
                <h2 class="text-white text-xl text-center">Scroll down to see the effect</h2>
            </header>
            <header class="bg-green-600 p-20">
                <h1 class="text-white text-4xl text-center">Header</h1>
                <h2 class="text-white text-xl text-center">Scroll down to see the effect</h2>
            </header>
            <header class="bg-red-600 p-20">
                <h1 class="text-white text-4xl text-center">Header</h1>
                <h2 class="text-white text-xl text-center">Scroll down to see the effect</h2>
            </header>
            <header class="bg-green-600 p-20">
                <h1 class="text-white text-4xl text-center">Header</h1>
                <h2 class="text-white text-xl text-center">Scroll down to see the effect</h2>
            </header>
        </header>

      
        <footer class="h-96 p-20 bg-red-600">
            <h1 class="text-white text-4xl text-center p-20">Footer</h1>
        </footer>
    </div>
  </div>
</template>
<style scoped>
.z-9999 {
  z-index: 100000;
}
</style>
