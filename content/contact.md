+++
description = "Send us the details for your event. We'll reply with a quote and plan."
title = "Contact"

+++
<form method="POST" action="https://formspree.io/howdy@rangerrunning.com" class="contact">
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
  <input type="hidden" name="_next" value="/thanks" />
  <input type="hidden" name="_subject" value="Running with Ranger" />
</form>
