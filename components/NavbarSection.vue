<!-- components/Navbar.vue -->

<template>
  <nav class="navbar">
    <div class="container">
      <h1 class="logo">My Portofolio</h1>
      <ul class="nav-links">
        <li><nuxt-link to="#hero">Home</nuxt-link></li>
        <li><nuxt-link to="#about">About</nuxt-link></li>
        <li><nuxt-link to="#contact">Contact</nuxt-link></li>
        <li><nuxt-link to="#projects">Projects</nuxt-link></li>
        <!-- Tambahkan link sesuai kebutuhan -->
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Navbar',
}
</script>

<style scoped>
/* Styling navbar */
.navbar {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
 /* Gradient warna latar belakang */
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); /* Shadow */
  z-index: 1000; /* Mengatur z-index agar navbar tetap di atas konten */
}

.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1200px;
  margin: 0 auto;
  padding: 10px 20px;
}

.logo {
  color: #fff;
  font-size: 1.8rem;
}

.nav-links {
  list-style-type: none;
  margin: 0;
  padding: 0;
  display: flex;
}

.nav-links li {
  margin-right: 20px;
}

.nav-links li:last-child {
  margin-right: 0;
}

a {
  color: #fff;
  text-decoration: none;
  padding: 10px 15px;
  transition: background-color 0.3s ease; /* Animasi untuk hover */
}

a:hover {
  background-color: rgba(255, 255, 255, 0.1); /* Warna latar belakang saat hover */
  border-radius: 5px; /* Sudut melengkung */
}
</style>
