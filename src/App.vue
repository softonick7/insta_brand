<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import HelloWorld from './components/HelloWorld.vue';

// COMPONENTS

import Header from './components/Global/Header.vue';
import Footer from './components/Global/Footer.vue';

// PAGES

import Home from './pages/Home.vue';
</script>

<template>
  <Header/>
  <main>
    <!-- <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Hello Vue 3 + Vite" /> -->
    <Home/>
  </main>
  <Footer/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}
</style>
