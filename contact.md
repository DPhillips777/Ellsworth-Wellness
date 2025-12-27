---
layout: default
title: "Contact"
description: "Contact & Bookings"
---

## Contact & Bookings

Fill out the form below and we’ll get back to you within 48 hours.

<!-- Replace the action URL with your Formspree form endpoint or your backend endpoint -->
<form class="contact-form" method="POST" action="https://formspree.io/f/{YOUR_FORMSPREE_ID}">
  <label>
    Name
    <input type="text" name="name" required />
  </label>
  <label>
    Email
    <input type="email" name="email" required />
  </label>
  <label>
    Message
    <textarea name="message" rows="5" required></textarea>
  </label>
  <button class="btn primary" type="submit">Send message</button>
</form>

Replace {YOUR_FORMSPREE_ID} with your Formspree ID (or replace the form action with your own backend endpoint).
