<template>
  <link rel='stylesheet' href='https://cdn.jsdelivr.net/npm/bootstrap@4.4.1/dist/css/bootstrap.min.css'>
  <section class="hero">
    <div class="container">
      <div class="card-body">
        <div>
          <h1 class="mb-3 mt-5">Hello Friends.</h1>
          <p class="custom-text-secondary mb-2">Saya Alvigo Wahyu Buana adalah seorang mahasiswa dari Universitas Amikom Yogyakarta, saya berasal dari Jawa Tengah. Saya suka bermain game dan mendengarkan musik. Saya juga suka pergi ke luar negeri sebulan sekali.</p>
          <p class="custom-text-secondary mb-2">Namun, karena saya tidak memiliki cukup biaya untuk hal tersebut, saya hanya rebahan di kosan saja.</p>
          <div class="mt-4">
            <a href="#contact-section" class="btn custom-btn">Follow</a>
            <a href="#message-section" class="btn custom-btn">Message</a>
          </div>
        </div>
        <div class="img-body" @mouseover="startAnimation" @mouseout="stopAnimation">
          <img src="~/assets/changli_icon.jpeg" class="rounded-circle img-fluid" ref="profileImage">
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'HeroSection',
  methods: {
    startAnimation() {
      this.$refs.profileImage.classList.add('rotate-on-hover');
    },
    stopAnimation() {
      this.$refs.profileImage.classList.remove('rotate-on-hover');
    }
  }
};
</script>

<style scoped>
.hero {
  padding: 100px;
}

.btn {
  margin-left: 10px;
}

.card-body {
  display: flex;
  align-items: center;
  margin-top: auto;
  margin-right: 70px;
  margin-bottom: 100px;
  color: #ffc400;
}

.img-body {
  display: flex;
  align-items: center;
  margin-top: 100px;
  width: 100%;
}

.custom-text-secondary {
  color: #000000; /* Ganti dengan warna teks yang Anda inginkan */
  margin-left: 5px;
  margin-right: 100px;
}

.custom-btn {
  background-color: #5f1515; /* Ganti dengan warna latar belakang tombol yang diinginkan */
  color: #ffffff; /* Warna teks tombol */
  border: none; /* Hapus border tombol */
  padding: 10px 20px; /* Padding tombol */
  border-radius: 5px; /* Ujung tombol melengkung */
  transition: background-color 0.3s ease; /* Transisi halus saat hover */
}

.custom-btn:hover {
  background-color: #7e4a4a; /* Warna latar belakang tombol saat hover */
}

.img-body:hover img {
  animation: flip 1s forwards;
}

@keyframes flip {
  0% {
    transform: rotateY(0deg);
  }
  100% {
    transform: rotateY(360deg);
  }
}
</style>
