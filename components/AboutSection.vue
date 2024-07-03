<template>
  <section class="about">
    <div class="container">
      <div class="about-content">
        <div class="about-row">
          <div class="about-column about-image-container">
            <img src="https://wuthering.wiki/img/rolecard_1205.png" alt="Alvigo Wahyu Buana" class="about-image">
          </div>
          <div class="about-column about-text">
            <h2 class="about-title">Nice To Meet You ^_^</h2>
            <p class="about-description">
              I'm Alvigo Wahyu Buana, a passionate Full Stack Developer based in Yogyakarta. With years of experience in web development, I specialize in creating dynamic and user-friendly applications.
            </p>
            <div class="about-skills">
              <h4 class="about-subtitle">Skills :</h4>
              <ul class="skills-list">
                <li><i class="fas fa-code"></i> Web Development</li>
                <li><i class="fas fa-database"></i> Database Management</li>
                <li><i class="fas fa-desktop"></i> UI/UX Design</li>
                <li><i class="fas fa-server"></i> Frontend Development</li>
              </ul>
            </div>
            <div class="about-experience">
              <h4 class="about-subtitle">Experience:</h4>
              <ul class="experience-list">
                <li><i class="fas fa-briefcase"></i> Full Stack Developer at XYZ Company (2020 - Present)</li>
                <li><i class="fas fa-briefcase"></i> Frontend Developer at ABC Company (2018 - 2020)</li>
              </ul>
            </div>
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
  padding: 60px 0;
}

.about-content {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.about-row {
  display: flex;
  flex-wrap: wrap;
  gap: 30px;
  align-items: center;
}

.about-column {
  flex: 1;
  min-width: 300px;
}

.about-image-container {
  text-align: center;
}

.about-image {
  width: 100%;
  border-radius: 8px;
  transition: transform 0.3s ease-in-out;
}

.about-image-container:hover .about-image {
  transform: scale(1.05);
}

.about-title {
  font-size: 2rem;
  margin-bottom: 20px;
  color: #000000;
}

.about-description {
  font-size: 1.1rem;
  line-height: 1.6;
  color: #000000;
  margin-bottom: 20px;
  text-align: justify;
}

.about-subtitle {
  font-size: 1.3rem;
  color: #000000;
  margin-bottom: 10px;
}

.skills-list,
.experience-list {
  list-style: none;
  padding-left: 0;
}

.skills-list li,
.experience-list li {
  margin-bottom: 10px;
  display: flex;
  align-items: center;
}

.skills-list li i,
.experience-list li i {
  margin-right: 8px;
  color: #000000;
}

.social-links {
  display: flex;
  gap: 10px;
  margin-top: 20px;
}

.social-link {
  font-size: 1.5rem;
  color: #000000;
  transition: color 0.3s;
}

.social-link:hover {
  color: #000000;
}

@media (max-width: 768px) {
  .about-column {
    min-width: 100%;
    text-align: center;
  }

  .about-title {
    font-size: 1.8rem;
  }

  .about-description {
    font-size: 1rem;
  }

  .about-subtitle {
    font-size: 1.2rem;
  }
}
</style>
