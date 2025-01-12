<template>
  <footer class="footer text-white q-pa-lg">
    <div class="row justify-between">
      <!-- Logo and Description -->
      <div class="col-12 col-md-3 custom">
        <img src="logo.png" alt="Fylo Logo" class="footer-logo q-mb-md" />
        <p class="footer-text">
          <q-icon name="place" color="white" class="q-mr-sm" />
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor<br />
          incididunt ut labore et dolore magna aliqua.
        </p>
      </div>

      <!-- Contact Information -->
      <div class="col-12 col-md-3">
        <div class="q-mb-sm">
          <q-icon name="phone" color="white" class="q-mr-sm" />
          +1-543-123-4567
        </div>
        <div class="q-mb-sm">
          <q-icon name="email" color="white" class="q-mr-sm" />
          example@fylo.com
        </div>
      </div>

      <!-- Navigation Links -->
      <div class="col-12 col-md-2">
        <p><a href="#" class="footer-link">About Us</a></p>
        <p><a href="#" class="footer-link">Jobs</a></p>
        <p><a href="#" class="footer-link">Press</a></p>
        <p><a href="#" class="footer-link">Blog</a></p>
      </div>
      <div class="col-12 col-md-2">
        <p><a href="#" class="footer-link">Contact Us</a></p>
        <p><a href="#" class="footer-link">Terms</a></p>
        <p><a href="#" class="footer-link">Privacy</a></p>
      </div>

      <!-- Social Media Links -->
     <div class="col-12 col-md-2 text-center">
  <!-- Facebook -->
  <a href="https://facebook.com" target="_blank" class="social-link">
    <img src="facebook.png" alt="Facebook" class="social-icon" />
  </a>

  <!-- Twitter -->
  <a href="https://twitter.com" target="_blank" class="social-link q-ml-md">
    <img src="twitter.png" alt="Twitter" class="social-icon" />
  </a>

  <!-- Instagram -->
  <a href="https://instagram.com" target="_blank" class="social-link q-ml-md">
    <img src="instagram.png" alt="Instagram" class="social-icon" />
  </a>
</div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>

.footer {
  padding-top: 3rem;
  font-family: "Open Sans", serif;
  background-color: #0b1524;
}

.footer-logo {
  max-width: 150px;
}

.footer-text {
  font-size: 14px;
  line-height: 1.6;
}

.footer-link {
  color: white;
  text-decoration: none;
  font-size: 14px;
  display: block;
  margin-bottom: 8px;
}

.footer-link:hover {
  text-decoration: underline;
}
.custom {
  text-align: start;
}
.social-link {
  display: inline-block;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.social-icon {
  width: 30px;
  height: 30px;
  border-radius: 50%;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.social-link:hover .social-icon {
  transform: scale(1.2);
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
}

.social-icon:hover {
  filter: brightness(1.2);
}


</style>
