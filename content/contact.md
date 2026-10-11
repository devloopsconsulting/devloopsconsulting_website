---
title: "Contact"
heading: "Book a free 30-minute call"
lede: "Pick a time that suits you, or send a short message about what you are working on. I reply within one business day."
description: "Contact DevLoops Consulting for DevOps, cloud, and robotics infrastructure work."
raw: true
hideCta: true
---

<div class="wrap">
  {{< booking >}}
  <div class="contact-grid">
    <div class="contact-info">
      <p>The first call is free and has no obligation. At the end of it, you will know if I can help and what the next step is.</p>
      <dl>
        <dt>Email</dt>
        <dd><a href="mailto:contact@devloopsconsulting.com">contact@devloopsconsulting.com</a></dd>
        <dt>Location</dt>
        <dd>Abu Dhabi, UAE. I work with teams in all time zones.</dd>
        <dt>LinkedIn</dt>
        <dd><a href="https://www.linkedin.com/in/ashwinmurali/" rel="noopener">Ashwin Thanalapati</a></dd>
      </dl>
    </div>
    <form class="form" action="https://formspree.io/f/xkgbgypy" method="POST">
      <div class="field">
        <label for="name">Name</label>
        <input type="text" id="name" name="name" autocomplete="name" required>
      </div>
      <div class="field">
        <label for="email">Work email</label>
        <input type="email" id="email" name="email" autocomplete="email" required>
      </div>
      <div class="field">
        <label for="company">Company</label>
        <input type="text" id="company" name="company" autocomplete="organization">
      </div>
      <div class="field">
        <label for="topic">What do you need help with?</label>
        <select id="topic" name="topic">
          <option>Robotics or autonomy infrastructure</option>
          <option>Cloud architecture or migration</option>
          <option>CI/CD and automation</option>
          <option>Cloud cost review</option>
          <option>Infrastructure audit</option>
          <option>Something else</option>
        </select>
      </div>
      <div class="field">
        <label for="message">Message</label>
        <textarea id="message" name="message" rows="5" required></textarea>
      </div>
      <button type="submit" class="btn btn-accent">Send message</button>
      <p class="hint">I use your details only to reply to you.</p>
    </form>
  </div>
</div>
