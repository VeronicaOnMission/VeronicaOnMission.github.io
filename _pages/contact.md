---
layout: single
permalink: /contact/
title: "Contact"
author_profile: true
---

<form name="gform" id="gform" enctype="text/plain" action="https://docs.google.com/forms/d/e/1FAIpQLSeQZHbJYkdtSrCMRMuc1LDtKgmrR6Jfol1KUzdZRjIIbIzQMQ/formResponse?" target="hidden_iframe" onsubmit="submitted=true;">
  <fieldset>
    <legend>Please contact me with any questions through one of my social links in the sidebar, or this form as needed.</legend>
    Name: <input type="text" size="30" name="entry.1166045863"><br>
    Email: <input type="text" size="30" name="entry.720425147"><br>
    Message: <textarea name="entry.220754968"></textarea>
	<input type="submit" name='submit' value="Submit Form">
  </fieldset>
</form>

<iframe name="hidden_iframe" id="hidden_iframe" style="display:none;" onload="if(submitted) {}"></iframe>

<script src="/assets/js/main.min.js"></script>
<script type="text/javascript">var submitted=false;</script>
<script type="text/javascript">
$('#gform').on('submit', function(e) {
  $('#gform *').fadeOut(2000);
  $('#gform').reset();
  $('#gform').prepend('Your information has been submitted...');
  });
</script>