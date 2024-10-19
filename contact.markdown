---
layout: default
title: Contact Me
---

<section class="contact-page">
  <h1>{{ page.title }}</h1>
  <p>Feel free to reach out to me through any of the platforms below.</p>

  <div class="contact-list">
    <div class="contact-item">
      <a href="https://www.linkedin.com/in/nickdurbin04" target="_blank">
        <i class="fab fa-linkedin fa-3x"></i>
        <h2>LinkedIn</h2>
      </a>
    </div>
    <div class="contact-item">
      <a href="https://github.com/nickdurbin04" target="_blank">
        <i class="fab fa-github fa-3x"></i>
        <h2>GitHub</h2>
      </a>
    </div>
    <div class="contact-item">
      <a href="https://dev.to/nickdurbin04" target="_blank">
        <i class="fab fa-dev fa-3x"></i>
        <h2>Dev.to</h2>
      </a>
    </div>
    <div class="contact-item">
      <a href="javascript:void(0);" onclick="showEmail()">
        <i class="fas fa-envelope fa-3x"></i>
        <h2>Email</h2>
      </a>
    </div>
  </div>

  <!-- Hidden Email Popup -->
  <div id="email-popup" class="email-popup">
    <p>nickdurbin04@gmail.com</p>
  </div>

</section>

<script>
  function showEmail() {
    var emailPopup = document.getElementById('email-popup');
    emailPopup.style.display = 'block'; // Show the popup

    // Hide the popup after 3 seconds
    setTimeout(function() {
      emailPopup.style.display = 'none';
    }, 3000);
  }
</script>
