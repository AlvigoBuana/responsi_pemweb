<template>
  <link rel='stylesheet' href='https://cdn.jsdelivr.net/npm/bootstrap@4.4.1/dist/css/bootstrap.min.css'>
  <section class="hero">
    <div class="container">
      <div class="card-body ">
        <div>
          <h1 class="mb-3 mt-5">Hello Friends.</h1>
          <p class="custom-text-secondary mb-2">Saya Alvigo Wahyu Buana adalah seorang mahasiswa dari Universitas Amikom Yogyakarta, saya berasal dari jawa tengah. Saya suka bermain game dan mendengarkan musik. saya juga suka pergi ke luar negri sebulan sekali.</p>
          <p class="custom-text-secondary mb-2">Namun, karena saya tidak memiliki cukup biaya untuk hal tersebut, saya hanya rebahan di kosan saja.</p>
          <div class="mt-4">
            <button class="btn custom-btn">Follow</button>
            <button class="btn custom-btn">Message</button>
          </div>
        </div>
        <div class="img-body">
          <img src="~/assets/changli_icon.jpeg" class="rounded-circle img-fluid">
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'HeroSection'
}
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
}

.img-body {
  display: flex;
  align-items: center;
  margin-top: 100px;
  width: 1000px;
}

.custom-text-secondary {
  color: #000000; /* Ganti dengan warna teks yang Anda inginkan */
  margin-left: 5px;
  margin-right: 100px;
}

.custom-text-muted {
  color: #000000; /* Ganti dengan warna teks yang Anda inginkan */
  font-size: 14px; /* Sesuaikan ukuran font jika diperlukan */
  margin-top: 0.5rem; /* Atur margin atas */
}

@media (max-width: 768px) {
  .card-body {
    flex-direction: column;
    align-items: center;
  }
}

/* Style khusus untuk tombol */
.custom-btn {
  background-color: #5f1515; /* Ganti dengan warna latar belakang tombol yang diinginkan */
  color: #ffffff; /* Warna teks tombol */
  border: none; /* Hapus border tombol */
  padding: 10px 20px; /* Padding tombol */
  border-radius: 5px; /* Ujung tombol melengkung */
  transition: background-color 0.3s ease; /* Transisi halus saat hover */
}

.custom-btn:hover {
  background-color: #0056b3; /* Warna latar belakang tombol saat hover */
}
</style>
