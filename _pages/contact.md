---
layout: single
permalink: /contact/
title: "Contact"
author_profile: true
---

## Prayer Request
<form name="gformprayer" id="gformprayer" enctype="text/plain" action="https://docs.google.com/forms/d/e/1FAIpQLScRAlEzSE7QrZiW1eMs6s7ITa3Fcp_GG2BNmyqy26s27seHgQ/formResponse?" target="hidden_iframeprayer" onsubmit="submitted=true;">
  <fieldset>
    <legend>Please be as detailed as you would like and know that your request will be kept confidential. The LORD is near to all who call on Him, to all who call on Him in truth. <i>Psalms 145:18</i></legend>
    Name: <input type="text" size="30" name="entry.1290604962"><br>
    Prayer request: <textarea name="entry.370420084"></textarea>
	<input type="submit" name='submit' value="Submit Prayer">
  </fieldset>
</form>

<iframe name="hidden_iframeprayer" id="hidden_iframeprayer" style="display:none;" onload="if(submitted) {}"></iframe>

<script src="/assets/js/main.min.js"></script>
<script type="text/javascript">var submitted=false;</script>
<script type="text/javascript">
  $('#gformprayer').on('submit', function(e) {
  $('#gformprayer *').fadeOut(2000);
  $('#gformprayer').prepend('Thank you for your willingness to ask for prayer.');
  });
</script>

## Connect
<form name="gformcontact" id="gformcontact" enctype="text/plain" action="https://docs.google.com/forms/d/e/1FAIpQLSeQZHbJYkdtSrCMRMuc1LDtKgmrR6Jfol1KUzdZRjIIbIzQMQ/formResponse?" target="hidden_iframecontact" onsubmit="submitted=true;">
  <fieldset>
    <legend>You can contact me via social media platforms on the sidebar or footer. This web form is also available for convenience. Please allow 1-2 days for a response.</legend>
    Name: <input type="text" size="30" name="entry.1166045863"><br>
    Email: <input type="text" size="30" name="entry.720425147"><br>
    Message: <textarea name="entry.220754968"></textarea>
	<input type="submit" name='submit' value="Submit Form">
  </fieldset>
</form>

<iframe name="hidden_iframecontact" id="hidden_iframecontact" style="display:none;" onload="if(submitted) {}"></iframe>

<script src="/assets/js/main.min.js"></script>
<script type="text/javascript">var submitted=false;</script>
<script type="text/javascript">
$('#gformcontact').on('submit', function(e) {
  $('#gformcontact *').fadeOut(2000);
  $('#gformcontact').prepend('Thank you for reaching out, your information has been submitted... :D');
  });
</script>