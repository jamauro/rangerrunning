+++
description = "Let's get running! Fill out the details below and smash that button."
title = "Contact"

+++
<form method="POST" action="https://formspree.io/jamauro@gmail.com" class="contact">
  <input type="name" name="name" placeholder="Name">
  <input type="email" name="email" placeholder="Email">
  <select name="groupsize" id="groupsize">
      <option value="" disabled selected>How many are you bringing with you?</option>
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
