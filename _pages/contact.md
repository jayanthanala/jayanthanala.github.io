---
layout: page
title: "Contact"
permalink: /contact/
---

I'd love to hear from you! Whether you have a question, want to collaborate, or just want to say hi, feel free to reach out.

<form id="contact-form" class="contact-form">
  <div class="form-group">
    <label for="name">Your Name</label>
    <input type="text" id="name" name="name" placeholder="John Doe" required>
  </div>
  <div class="form-group">
    <label for="email">Your Email</label>
    <input type="email" id="email" name="email" placeholder="john@example.com" required>
  </div>
  <div class="form-group">
    <label for="message">Message</label>
    <textarea id="message" name="message" rows="5" placeholder="Your message here..." required></textarea>
  </div>
  <button type="submit" class="submit-btn">Send Message</button>
</form>

<script>
document.getElementById('contact-form').onsubmit = function(e) {
  e.preventDefault();
  const name = document.getElementById('name').value;
  const email = document.getElementById('email').value;
  const message = document.getElementById('message').value;
  const subject = encodeURIComponent('Portfolio Contact from ' + name);
  const body = encodeURIComponent('From: ' + name + '\nEmail: ' + email + '\n\n' + message);
  window.location.href = 'mailto:jayanthanala@gmail.com?subject=' + subject + '&body=' + body;
};
</script>

---

### Other Ways to Reach Me

- **Email**: [jayanthanala@gmail.com](mailto:jayanthanala@gmail.com)
- **LinkedIn**: [linkedin.com/in/jayanthanala](https://linkedin.com/in/jayanthanala)
- **GitHub**: [github.com/jayanthanala](https://github.com/jayanthanala)
