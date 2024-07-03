<template>
    <div class="container">
      <div class="row gutters-sm">
        <!-- Gambar di sebelah kiri -->
        <div class="col-md-4 mb-3 d-flex align-items-stretch">
          <div class="card border-0 shadow h-100">
            <img src="/assets/foto.jpg" class="card-img-top h-100" alt="...">
          </div>
        </div>
  
        <!-- Card di sebelah kanan dengan progress bar -->
        <div class="col-md-8 mt-3">
          <div class="card h-100 border-0 shadow">
            <div class="card-body">
              <h6 class="d-flex align-items-center mb-3">Project Status</h6>
              
              <div class="mb-3">
                <div class="d-flex justify-content-between align-items-center">
                  <div><small>Web Design</small></div>
                  <div><span class="fw-bold">80%</span></div>
                </div>
                <div class="progress" style="height: 8px;">
                  <div class="progress-bar bg-primary" role="progressbar" style="width: 80%" aria-valuenow="80" aria-valuemin="0" aria-valuemax="100"></div>
                </div>
              </div>
              
              <div class="mb-3">
                <div class="d-flex justify-content-between align-items-center">
                  <div><small>Website Markup</small></div>
                  <div><span class="fw-bold">72%</span></div>
                </div>
                <div class="progress" style="height: 8px;">
                  <div class="progress-bar bg-primary" role="progressbar" style="width: 72%" aria-valuenow="72" aria-valuemin="0" aria-valuemax="100"></div>
                </div>
              </div>
              
              <div class="mb-3">
                <div class="d-flex justify-content-between align-items-center">
                  <div><small>One Page</small></div>
                  <div><span class="fw-bold">89%</span></div>
                </div>
                <div class="progress" style="height: 8px;">
                  <div class="progress-bar bg-primary" role="progressbar" style="width: 89%" aria-valuenow="89" aria-valuemin="0" aria-valuemax="100"></div>
                </div>
              </div>
              
              <div class="mb-3">
                <div class="d-flex justify-content-between align-items-center">
                  <div><small>Mobile Template</small></div>
                  <div><span class="fw-bold">55%</span></div>
                </div>
                <div class="progress" style="height: 8px;">
                  <div class="progress-bar bg-primary" role="progressbar" style="width: 55%" aria-valuenow="55" aria-valuemin="0" aria-valuemax="100"></div>
                </div>
              </div>
              
              <div class="mb-3">
                <div class="d-flex justify-content-between align-items-center">
                  <div><small>Backend API</small></div>
                  <div><span class="fw-bold">66%</span></div>
                </div>
                <div class="progress" style="height: 8px;">
                  <div class="progress-bar bg-primary" role="progressbar" style="width: 66%" aria-valuenow="66" aria-valuemin="0" aria-valuemax="100"></div>
                </div>
              </div>
              
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    // Component properties
  }
  </script>
  
  <style scoped>
  .card {
    background-color: #f8f9fa; /* Background color */
    padding: 20px;
    transition: transform 0.3s ease;
  }
  
  .card:hover {
    transform: translateY(-5px); /* Efek mengangkat saat hover */
  }
  
  .progress-bar {
    transition: width 0.6s ease;
  }
  
  .progress-bar.bg-primary {
    background-image: linear-gradient(45deg, #007bff, #6c757d); /* Gradient warna background progress */
  }
  
  .progress {
    border-radius: 10px; /* Sudut bulat pada progress bar */
  }
  
  .card-img-top {
    object-fit: cover; /* Menjaga proporsi gambar */
  }
  </style>
  