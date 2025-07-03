---
layout: single
permalink: /contact/
title: "Contact"
author_profile: true
---

<form method="post" name="myemailform" action="\_php\form-to-email.php">
  <form action="MAILTO:mrbrentconner@gmail.com" method="post" enctype="text/plain">
  <fieldset>
    <legend>Description</legend>
    Name: <input type="text" size="30"><br>
    Email: <input type="text" size="30"><br>
    Message: <textarea name="message"></textarea>
	<input type="submit" name='submit' value="Submit Form">
  </fieldset>
</form>