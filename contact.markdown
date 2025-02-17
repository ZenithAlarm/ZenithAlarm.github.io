---
layout: page
title: Contact us
permalink: /contact/
---
<!-- Materialize CSS -->
<link href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css" rel="stylesheet">

<!-- Materialize JS -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>

# Contact Us

We’d love to hear from you! Please fill out the form below and we'll get back to you as soon as possible.

<form action="https://formspree.io/f/{your-form-id}" method="POST">
  <!-- First Name -->
  <div class="input-field">
    <input type="text" id="first_name" name="first_name" required>
    <label for="first_name">First Name</label>
  </div>

  <!-- Last Name -->
  <div class="input-field">
    <input type="text" id="last_name" name="last_name" required>
    <label for="last_name">Last Name</label>
  </div>

  <!-- Email -->
  <div class="input-field">
    <input type="email" id="email" name="_replyto" required>
    <label for="email">Email</label>
  </div>

  <!-- Request -->
  <div class="input-field">
    <textarea id="request" name="request" class="materialize-textarea" required></textarea>
    <label for="request">Request</label>
  </div>

  <!-- Submit Button -->
  <button type="submit" class="btn waves-effect waves-light">Send Message</button>
</form>

<script>
  // Initialize Materialize form features
  M.updateTextFields();  // For floating labels to work properly
</script>