---
layout: layouts/post.njk
title: Forms
templateClass: tmpl-post
eleventyNavigation:
  key: Forms
  order: 5
---

<br><br>
<div class="container">
<h4>Contact Form</h4><br>

<form name="contact" method="POST" data-netlify="true">
  <div class="form-group">
    <label for="name1" class="w-50">Your name
    <input type="text" class="form-control" id="name1" aria-describedby="nameHelp" name= "name" placeholder="Enter name" required></label>
  </div>
  <div class="form-group">
    <label for="email1" class="w-50">Email address
    <input type="email" name="email" class="form-control" id="email1" aria-describedby="emailHelp" placeholder="Enter email" required></label>
  </div>
  <div class="form-group">
    <label for="tel1" class="w-50">Phone
    <input type="tel" name="phone" class="form-control" id="tel1" placeholder="Phone" max="11"></label>
  </div>
  <div class="form-group">
    <label for="message1" class="w-50">Message
    <textarea name="message" type="text" class="form-control" id="message1" rows="3" maxlenght="50"></textarea></label>
  </div>
  <div class="form-check">
    <label class="w-100" for="exampleCheck1">Agree to send this data? Check the box<input type="checkbox" class="form-check-input d-flex" id="exampleCheck1" required></label>
  </div>
  <br>
  <button type="submit" class="btn btn-primary">Submit</button>
</form>
</div>
