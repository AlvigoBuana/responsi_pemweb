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
        
        <!-- Formulir Kontak -->
        <form class="contact-form" @submit.prevent="submitForm">
          <div class="form-group">
            <label for="name">Name:</label>
            <input type="text" id="name" v-model="formData.name" required>
          </div>
          <div class="form-group">
            <label for="email">Email:</label>
            <input type="email" id="email" v-model="formData.email" required>
          </div>
          <div class="form-group">
            <label for="message">Message:</label>
            <textarea id="message" v-model="formData.message" rows="5" required></textarea>
          </div>
          <button type="submit">Send Message</button>
        </form>
        
        <!-- Peta Lokasi -->
        <div class="map">
          <!-- Tambahkan kode untuk peta lokasi jika diperlukan -->
          <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3953.4112299593534!2d110.36864691442038!3d-7.778828579101662!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e7b8e6b2f96d3d1%3A0xc8f0e3eb6a43fca5!2sYogyakarta%2C%20Condong%20Catur%2C%20Sleman%2C%20Daerah%20Istimewa%20Yogyakarta!5e0!3m2!1sen!2sid!4v1625225401857!5m2!1sen!2sid" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
        </div>
        
        <!-- Social Links -->
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
  name: 'ContactSection',
  data() {
    return {
      formData: {
        name: '',
        email: '',
        message: ''
      }
    };
  },
  methods: {
    submitForm() {
      // Logika untuk mengirim formulir bisa ditambahkan di sini
      console.log('Form submitted with data:', this.formData);
      // Reset formulir setelah dikirim (opsional)
      this.formData.name = '';
      this.formData.email = '';
      this.formData.message = '';
    }
  }
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

.contact-form {
  margin-top: 30px;
}

.form-group {
  margin-bottom: 20px;
}

label {
  display: block;
  margin-bottom: 5px;
}

input[type="text"],
input[type="email"],
textarea {
  width: 100%;
  padding: 10px;
  font-size: 1rem;
  border: 1px solid #ccc;
  border-radius: 5px;
}

textarea {
  resize: vertical;
}

button[type="submit"] {
  background-color: #007bff;
  color: #fff;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

button[type="submit"]:hover {
  background-color: #0056b3;
}

.map {
  margin-top: 30px;
  text-align: center;
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
