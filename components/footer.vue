<template>
    <footer class="footer">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-12 text-center">
            <p class="footer-text">&copy; 2024 Alvigo Wahyu Buana. All rights reserved.</p>
          </div>
          <div class="col-12 text-center">
            <a href="#" class="footer-link">Privacy Policy</a>
            <a href="#" class="footer-link">Terms of Service</a>
          </div>
        </div>
      </div>
    </footer>
  </template>
  
  <script>
  export default {
    name: 'footer'
  }
  </script>
  
  <style scoped>
  .footer {
    background-color: #f8f9fa00;
    padding: 20px 0;
    width: 100%;
    position: relative;
  }
  
  .footer-text {
    margin: 0;
    color: #000000;
  }
  
  .footer-link {
    color: #003cff;
    margin: 0 10px;
    text-decoration: none;
  }
  
  .footer-link:hover {
    text-decoration: underline;
  }
  
  @media (max-width: 768px) {
    .footer-link {
      display: block;
      margin: 5px 0;
    }
  }
  </style>
  