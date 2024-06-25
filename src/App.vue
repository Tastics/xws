<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Nav from './components/Nav.vue'
import Footer from './components/Footer.vue'
</script>

<template>
    <!-- Navbar -->
    <Nav></Nav>
    <RouterView />
    <Footer></Footer>
</template>

<style scoped></style>
