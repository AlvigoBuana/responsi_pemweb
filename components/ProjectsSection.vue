<template>
  <section class="projects">
    <div class="container">
      <h2 class="section-title">My Projects</h2>
      <div class="project-list">
        <div class="project">
          <h3 class="project-title">Project 1</h3>
          <p class="project-description">Description of Project 1 goes here.</p>
          <a href="#" class="btn btn-primary">View Project</a>
        </div>
        <div class="project">
          <h3 class="project-title">Project 2</h3>
          <p class="project-description">Description of Project 2 goes here.</p>
          <a href="#" class="btn btn-primary">View Project</a>
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
  background-color: #fff;
  border-radius: 8px;
  padding: 20px;
  margin-bottom: 20px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

.project-title {
  font-size: 1.8rem;
  margin-bottom: 10px;
}

.project-description {
  font-size: 1.1rem;
  line-height: 1.6;
  margin-bottom: 15px;
}

.btn-primary {
  background-color: #007bff;
  color: #fff;
  border: none;
  padding: 8px 16px;
  border-radius: 4px;
  text-decoration: none;
  display: inline-block;
  transition: background-color 0.3s ease;
}

.btn-primary:hover {
  background-color: #0056b3;
}
</style>
