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
    <div class="hero-section">
      <div class="hero-image">
        <img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.iconfinder.com%2Ficons%2F282803%2Fpython_logo_icon&psig=AOvVaw3t5-AsAt0wGs-9YDGsnLaf&ust=1714248909164000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCICq4_vY4IUDFQAAAAAdAAAAABAE" alt="Hero Image">
      </div>
      <div class="hero-text">
        <p>Welcome to the SALON for your nails. We offer a wide range of services to enhance your nail experience.</p>
      </div>
    </div>
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
 padding-top: 60px; /* Adjust based on the height of your navbar */
}

.navbar {
 position: fixed;
 top: 0;
 left: 0;
 width: 100%;
 background-color: #f8f9fa;
 padding: 1rem 0;
 z-index: 1000; /* Ensures the navbar stays on top of other content */
}

.navbar ul {
 list-style-type: none;
 padding: 0;
 display: flex;
 justify-content: space-between; /* Distributes space evenly between the links */
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

/* Hero Section */
.hero-section {
 display: flex;
 justify-content: space-between;
 align-items: center;
 padding: 2rem;
 background-color: #f8f9fa;
}

.hero-image img {
 max-width: 50%; /* Adjust as needed */
 height: auto;
}

.hero-text p {
 max-width: 50%; /* Adjust as needed */
}
</style>
