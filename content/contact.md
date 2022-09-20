---
title: "Contact Me"
---

<form name="contact" method="POST" data-netlify="true" data-netlify-recaptcha="true">
        <div class="mb-3">
          <label for="name">Name:</label>
          <input type="text" class="form-control" id="name" name="name" required>
        </div>
        <div class="mb-3">
          <label for="email">Email:</label>
          <input type="email" class="form-control" id="email" name="email" required>
        </div>
        <div class="mb-3">
          <label for="message">Message:</label>
          <textarea class="form-control" rows="10" id="message" name="message" required></textarea>
        </div>
        <div class="mb-3">
          <div data-netlify-recaptcha="true"></div>
        </div>
        <button type="submit" class="btn btn-primary">Submit</button>
      </form>