<template>
  <section class="projects">
    <div class="container">
      <h2 class="section-title mt-5">My Projects</h2>
      <div class="row">
        <div class="col-lg-6 mb-4">
          <div class="project">
            <h3 class="project-title mb-4">Project 1</h3>
            <img src="https://i.pinimg.com/originals/57/98/de/5798de897c75ac5055ad170f15aba548.jpg" alt="Project 1" class="project-image">
            <p class="project-description">Description of Project 1 goes here.</p>
            <p class="project-tech">Technologies used: HTML, CSS, JavaScript</p>
            <div class="project-buttons">
              <a href="#" class="btn btn-primary">View Project</a>
              <a href="#" class="btn btn-secondary">Demo</a>
            </div>
          </div>
        </div>
        <div class="col-lg-6 mb-4">
          <div class="project">
            <h3 class="project-title mb-4">Project 2</h3>
            <img src="https://i.pinimg.com/originals/c4/f8/64/c4f8646bef295972f4360172b76bdb6f.jpg" alt="Project 2" class="project-image">
            <p class="project-description">Description of Project 2 goes here.</p>
            <p class="project-tech">Technologies used: Vue.js, Node.js, MongoDB</p>
            <div class="project-buttons">
              <a href="#" class="btn btn-primary">View Project</a>
              <a href="#" class="btn btn-secondary">Demo</a>
            </div>
          </div>
        </div>
        <!-- Add more projects as needed -->
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ProjectsSection'
}
</script>

<style scoped>
.projects {
  padding: 50px 0;
}

.section-title {
  font-size: 2.5rem;
  text-align: center;
  margin-bottom: 30px;
}

.project {
  background-color: #ffffff33;
  border-radius: 8px;
  padding: 20px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  height: 100%; /* Menyesuaikan ketinggian proyek */
  margin : 20px
}

.project-title {
  font-size: 1.8rem;
  margin-bottom: 10px;
}

.project-image {
  width: 100%;
  border-radius: 8px;
  margin-bottom: 15px;
}

.project-description {
  font-size: 1.1rem;
  line-height: 1.6;
  margin-bottom: 10px;
}

.project-tech {
  font-size: 0.9rem;
  color: #666;
  margin-bottom: 10px;
}

.project-buttons {
  margin-top: 15px;
  margin-bottom: 10px;
}

.btn {
  padding: 8px 16px;
  border-radius: 4px;
  text-decoration: none;
  display: inline-block;
  transition: background-color 0.3s ease;
}

.btn-primary {
  background-color: #007bff;
  color: #fff;
  border: none;
}

.btn-primary:hover {
  background-color: #0056b3;
}

.btn-secondary {
  background-color: #6c757d;
  color: #fff;
  border: none;
  margin-left: 10px;
}

.btn-secondary:hover {
  background-color: #545b62;
}
</style>
