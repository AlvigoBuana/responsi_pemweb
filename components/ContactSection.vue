<template>
  <section class="hero">
    <div class="container">
      <div class="main-body">
        <div>
          <h1 class="mb-5 text-center">CONTACT ME</h1>
        </div>

        <!-- Contact Card -->
        <div class="card mt-5" id="contact-section" >
          <h2 class="card-title text-center">Contact</h2>
          <ul class="list-group list-group-flush">
            <li class="list-group-item bg-transparent d-flex justify-content-between align-items-center flex-wrap">
              <h6 class="mb-0">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-globe mr-2 icon-inline">
                  <circle cx="12" cy="12" r="10"></circle>
                  <line x1="2" y1="12" x2="22" y2="12"></line>
                  <path d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"></path>
                </svg>
                Website
              </h6>
              <a href="https://github.com/AlvigoBuana" class="custom-text-secondary">https://github.com/AlvigoBuana</a>
            </li>
            <hr>
            <li class="list-group-item bg-transparent d-flex justify-content-between align-items-start">
              <div class="d-flex align-items-center">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-github mr-2 icon-inline">
                  <path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path>
                </svg>
                <h6 class="mb-0">Github</h6>
              </div>
              <a href="https://github.com/AlvigoBuana" class="custom-text-secondary mt-2">https://github.com/AlvigoBuana</a>
            </li>
            <hr>
            <li class="list-group-item bg-transparent d-flex justify-content-between align-items-center flex-wrap">
              <h6 class="mb-0">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-twitter mr-2 icon-inline text-info">
                  <path d="M23 3a10.9 10.9 0 0 1-3.14 1.53 4.48 4.48 0 0 0-7.86 3v1A10.66 10.66 0 0 1 3 4s-4 9 5 13a11.64 11.64 0 0 1-7 2c9 5 20 0 20-11.5a4.5 4.5 0 0 0-.08-.83A7.72 7.72 0 0 0 23 3z"></path>
                </svg>
                Twitter
              </h6>
              <a class="custom-text-secondary">@AlvigoBuana</a>
            </li>
            <hr>
            <li class="list-group-item bg-transparent d-flex justify-content-between align-items-center flex-wrap">
              <h6 class="mb-0">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-instagram mr-2 icon-inline text-danger">
                  <rect x="2" y="2" width="20" height="20" rx="5" ry="5"></rect>
                  <path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"></path>
                  <line x1="17.5" y1="6.5" x2="17.51" y2="6.5"></line>
                </svg>
                Instagram
              </h6>
              <a href="https://www.instagram.com/alvgwb_/" class="custom-text-secondary">@alvgwb_</a>
            </li>
            <hr>
            <li class="list-group-item bg-transparent d-flex justify-content-between align-items-center flex-wrap" id="message-section">
              <h6 class="mb-0">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-facebook mr-2 icon-inline text-primary">
                  <path d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"></path>
                </svg>
                Facebook
              </h6>
              <a href="https://web.facebook.com/Alvigo.07/?locale=id_ID" class="custom-text-secondary">Alvigo</a>
            </li>
            <hr>
          </ul>
        </div>
        <!-- Message Me Card -->
        <div class="card mt-5">
          <h2 class="card-title text-center">Message Me</h2>
          <div class="card-body">
            <form>
              <div class="form-group">
                <label for="name">Name</label>
                <input type="text" class="form-control" id="name" placeholder="Your Name">
              </div>
              <div class="form-group">
                <label for="email">Email</label>
                <input type="email" class="form-control" id="email" placeholder="Your Email">
              </div>
              <div class="form-group">
                <label for="message">Message</label>
                <textarea class="form-control" id="message" rows="4" placeholder="Your Message"></textarea>
              </div>
              <button type="submit" class="btn btn-primary">Send</button>
            </form>
          </div>
        </div>

      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ContactSection',
}
</script>

<style scoped>
.hero {
  text-align: center;
  padding: 100px 0;
}

.card {
  background: #c0262641;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  border-radius: 14px;
  padding: 20px;
  margin-bottom: 100px;
}

.list-group-item {
  background: transparent;
  border: none;
}

.card-title {
  font-size: 1.5rem;
  margin-top: 15px;
}

.custom-text-secondary {
  color: #000000;
}
.form-group{
  margin-bottom: 15px;
  text-align: left;
}
.form-control {
  background: transparent;
  border: 1px solid #000000;
  color: #000000;
}

.form-control::placeholder {
  color: #ffffff9f;
}

.btn-primary {
  background-color: #7e4a4a;
  border-color: #7e4a4a;
  color: #fff;
}

.btn-primary:hover {
  background-color: #7e4a4a;
  border-color: #7e4a4a;
}

@media (max-width: 768px) {
  .card-title {
    font-size: 1.3rem;
  }

  .form-control {
    font-size: 0.9rem;
  }
}
</style>
