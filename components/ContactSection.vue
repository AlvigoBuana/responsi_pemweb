<template>
  <section class="contact">
    <div class="container">
      <h2 class="section-title">Contact Me</h2>
      <div class="contact-content">
        <p class="contact-info">
          Email: alvigobuana@gmail.com
        </p>
        <p class="contact-info">
          Phone: 0811 1111 1111
        </p>
        <p class="contact-info">
          Address: Condong Catur, Sleman, Yogyakarta
        </p>
        <div class="social-links">
          <a href="https://twitter.com/AlvigoBuana" target="_blank" class="social-link"><i class="fab fa-twitter"></i></a>
          <a href="https://github.com/AlvigoBuana" target="_blank" class="social-link"><i class="fab fa-github"></i></a>
          <a href="https://instagram.com/alvgwb_07" target="_blank" class="social-link"><i class="fab fa-instagram"></i></a>
          <a href="https://facebook.com/Alvigo" target="_blank" class="social-link"><i class="fab fa-facebook"></i></a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ContactSection'
}
</script>

<style scoped>
.contact {
  padding: 50px 0;
}

.section-title {
  font-size: 2.5rem;
  text-align: center;
  margin-bottom: 30px;
}

.contact-info {
  font-size: 1.1rem;
  margin-bottom: 15px;
}

.social-links {
  margin-top: 20px;
  text-align: center;
}

.social-link {
  font-size: 1.5rem;
  margin: 0 10px;
  color: #333;
}

.social-link:hover {
  color: #007bff;
}
</style>
