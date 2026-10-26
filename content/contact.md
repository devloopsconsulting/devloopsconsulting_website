---
title: "Contact"
heading: "Book a free 30-minute fit call"
lede: "Pick a time that suits you, or send a short message about what you are working on. I reply within one business day."
description: "Contact DevLoops Consulting for DevOps, cloud, and robotics infrastructure work."
raw: true
hideCta: true
---

<div class="wrap">
  {{< booking >}}
  <div class="contact-grid">
    <div class="contact-info">
      <p>The first call is free and has no obligation. You tell me where you are and where you need to be. At the end, you know if I can help, and if a diagnostic is the right next step.</p>
      <p>Want to see the work first? Ask for the 15-minute demo: one robot mission, traced end to end, from ROS 2 on the robot to the cloud.</p>
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
          <option>Production Readiness Diagnostic</option>
          <option>Fleet observability</option>
          <option>Release pipeline and OTA updates</option>
          <option>AI or GPU platform</option>
          <option>Cloud and GPU cost</option>
          <option>Fractional platform lead</option>
          <option>The 15-minute mission trace demo</option>
          <option>Something else</option>
        </select>
      </div>
      <div class="field">
        <label for="stage">Company stage</label>
        <select id="stage" name="stage">
          <option>Pre-seed or seed</option>
          <option>Series A or B</option>
          <option>Later stage or enterprise</option>
          <option>Public sector</option>
        </select>
      </div>
      <div class="field">
        <label for="start">When do you want to start?</label>
        <select id="start" name="start">
          <option>This month</option>
          <option>In 1 to 3 months</option>
          <option>Later, I am planning ahead</option>
        </select>
      </div>
      <div class="field">
        <label for="message">What are you building, and what is in the way?</label>
        <textarea id="message" name="message" rows="5" required></textarea>
      </div>
      <button type="submit" class="btn btn-accent">Send message</button>
      <p class="hint">I use your details only to reply to you.</p>
    </form>
  </div>
</div>
