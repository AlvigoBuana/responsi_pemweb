<template>
  <section class="about">
    <div class="container">
      <div class="about-content">
        <div class="about-row">
          <div class="about-column about-image-container">
            <img src="https://wuthering.wiki/img/rolecard_1205.png" alt="Alvigo Wahyu Buana" class="about-image">
          </div>
          <div class="about-column about-text">
            <h2 >Nice To Meet You ^_^ </h2>
            <p class="about-description">
              I'm Alvigo Wahyu Buana, a passionate Full Stack Developer based in Yogyakarta. With years of experience in web development, I specialize in creating dynamic and user-friendly applications.
            </p>

            <div class="about-skills">
              <h4>Skills :</h4>
              <ul class="skills-list">
                <li><i class="fas fa-code"></i> Web Development</li>
                <li><i class="fas fa-database"></i> Database Management</li>
                <li><i class="fas fa-desktop"></i> UI/UX Design</li>
                <li><i class="fas fa-server"></i> Backend Development</li>
              </ul>
            </div>
            <div class="about-experience">
              <h4>Experience:</h4>
              <ul class="experience-list">
                <li><i class="fas fa-briefcase"></i> Full Stack Developer at XYZ Company (2020 - Present)</li>
                <li><i class="fas fa-briefcase"></i> Frontend Developer at ABC Company (2018 - 2020)</li>
              </ul>
            </div>
            <div class="social-links">
              <h4>Find me on:</h4>
              <a href="https://twitter.com/AlvigoBuana" target="_blank" class="social-link"><i class="fab fa-twitter"></i></a>
              <a href="https://github.com/AlvigoBuana" target="_blank" class="social-link"><i class="fab fa-github"></i></a>
              <a href="https://instagram.com/alvgwb_07" target="_blank" class="social-link"><i class="fab fa-instagram"></i></a>
              <a href="https://facebook.com/Alvigo" target="_blank" class="social-link"><i class="fab fa-facebook"></i></a>
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
  padding: 50px 0;
}

.section-title {
  font-size: 2.5rem;
  text-align: center;
  margin-bottom: 30px;
}

.about-content {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.about-row {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
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
  max-width: 900px;
  border-radius: 8px;
  transition: transform 0.3s ease-in-out;
}

.about-image-container:hover .about-image {
  transform: scale(1.05);
}

.about-text {
  text-align: left;
}

.about-description {
  font-size: 1.1rem;
  line-height: 1.6;
  color: #555;
  margin-bottom: 20px;
}

.about-skills,
.about-experience,
.about-education {
  margin-top: 20px;
}

.skills-list,
.experience-list,
.education-list {
  list-style: none;
  padding-left: 0;
}

.skills-list li,
.experience-list li,
.education-list li {
  margin-bottom: 10px;
}

.skills-list li i,
.experience-list li i,
.education-list li i {
  margin-right: 8px;
  color: #007bff;
}

.social-links {
  display: flex;
  gap: 10px;
  margin-top: 20px;
}

.social-link {
  font-size: 1.5rem;
  color: #333;
}

.social-link:hover {
  color: #007bff;
}
</style>
