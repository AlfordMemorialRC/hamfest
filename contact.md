---
title: Contact Form
layout: default
---
# Contact Form

<div class="container">
  <form id="fs-frm" name="contact-form" accept-charset="utf-8" action="https://formspree.io/f/{{ site.formspree_id }}" method="post">
    <label for="fname">First Name</label>
    <input type="text" id="fname" name="firstname" required="true" placeholder="Your name..">
    <label for="lname">Last Name</label>
    <input type="text" id="lname" name="lastname" required="true" placeholder="Your last name..">
    <label for="callsign">Callsign</label>
    <input type="text" id="callsign" name="callsign" placeholder="Your callsign..">
    <label for="email">Email</label>
    <input type="text" id="email" name="_replyto" placeholder="Your email..">
    <label for="comments">Comments</label>
    <textarea id="comments" name="comments" required="true" placeholder="Write something here.." style="height:200px"></textarea>
    <input type="submit" value="Submit">
  </form>
</div>
