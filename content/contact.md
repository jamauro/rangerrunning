+++
description = "Send us the details for your event. We'll reply with a quote and plan."
title = "Contact"

+++
<form id="subscribe" name="contact" method="POST" netlify-honeypot="bot-field" action="/thanks" netlify>
  <span class="hidden">
    <label>Don’t fill this out if you're human: <input name="bot-field" /></label>
  </span>
  <input type="name" name="name" placeholder="Name">
  <input type="email" name="email" placeholder="Email">
  <select name="groupsize" id="groupsize">
      <option value="" disabled selected>How many are in your group?</option>
      <option value="1-10">1-10</option>
      <option value="11-50">11-50</option>
      <option value="51-100">51-100</option>
      <option value="100+">100+</option>
  </select>
  <textarea name="message" placeholder="Any notes you want to add (optional)"></textarea>
  <button type="submit">Send</button>
</form>

