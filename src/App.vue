<template>
 <div class="landing-page">
    <nav class="navbar">
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About Us</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#contact">Contact Us</a></li>
      </ul>
    </nav>
    <h1>Nail Treatment</h1>
    <p>Welcome to the SALON for your nails</p>
 </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
 name: 'App',
});
</script>

<style scoped>
.landing-page {
 text-align: center;
 padding: 2rem;
 padding-top: 60px; 
}

.navbar {
 position: fixed;
 top: 0;
 left: 0;
 width: 100%;
 background-color: #f8f9fa;
 padding: 1rem 0;
 z-index: 1000;
}

.navbar ul {
 list-style-type: none;
 padding: 0;
 display: flex;
 justify-content: space-between; 
}

.navbar li {
 margin: 0 1rem;
}

.navbar a {
 text-decoration: none;
 color: #333;
}

.navbar a:hover {
 color: #007bff;
}
</style>
