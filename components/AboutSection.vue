<template>
  <section class="about">
    <div class="container">
      <h2 class="section-title">About Me</h2>
      <div class="about-content">
        <div class="row">
          <div class="col-md-6">
            <img src="https://wuthering.wiki/img/rolecard_1205.png" alt="Alvigo Wahyu Buana" class="about-image">
          </div>
          <div class="col-md-6">
            <p class="about-description">
              I'm Alvigo Wahyu Buana, a passionate Full Stack Developer based in Yogyakarta. With years of experience in web development, I specialize in creating dynamic and user-friendly applications.
            </p>
            <p class="about-description">
              In my spare time, I enjoy exploring new technologies and contributing to open-source projects.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'AboutSection'
}
</script>

<style scoped>
.about {
  padding: 50px 0;
}

.section-title {
  font-size: 2.5rem;
  text-align: center;
  margin-bottom: 30px;
}

.about-image {
  width: 100%;
  border-radius: 8px;
}

.about-description {
  font-size: 1.1rem;
  line-height: 1.6;
}
</style>
