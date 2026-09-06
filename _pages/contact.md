---
layout: single
permalink: /contact/
title: "Contact"
author_profile: true
---

## Prayer Request
<form name="gformprayer" id="gformprayer" enctype="text/plain" action="https://docs.google.com/forms/d/e/1FAIpQLSdaRfXGdzhVYsvXq4dFmQTMxyPD8IKrR4gR4l46Svt7rcD1gg/formResponse?" target="hidden_iframeprayer" onsubmit="submitted=true;">
  <fieldset>
    <legend>Please be as detailed as you would like and know that your request will be kept confidential. The LORD is near to all who call on Him, to all who call on Him in truth. <i>Psalms 145:18</i></legend>
    Name: <input type="text" size="30" name="entry.773669013"><br>
    Prayer request: <textarea name="entry.822590760"></textarea>
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
<form name="gformconnect" id="gformconnect" enctype="text/plain" action="https://docs.google.com/forms/d/e/1FAIpQLSe2TSXbJHXWlGEMh7DaDqQknK_qT4r7ozaiec5hn6-6DYTqvQ/formResponse?" target="hidden_iframecontact" onsubmit="submitted=true;">
  <fieldset>
    <legend>You can contact me via social media platforms on the sidebar or footer. This web form is also available for convenience. Please allow 1-2 days for a response.</legend>
    Name: <input type="text" size="30" name="entry.1764945982"><br>
    Email: <input type="text" size="30" name="entry.147314099"><br>
    Message: <textarea name="entry.966876538"></textarea>
	<input type="submit" name='submit' value="Submit Form">
  </fieldset>
</form>

<iframe name="hidden_iframecontact" id="hidden_iframecontact" style="display:none;" onload="if(submitted) {}"></iframe>

<script src="/assets/js/main.min.js"></script>
<script type="text/javascript">var submitted=false;</script>
<script type="text/javascript">
$('#gformconnect').on('submit', function(e) {
  $('#gformconnect *').fadeOut(2000);
  $('#gformconnect').prepend('Thank you for reaching out, your information has been submitted... :D');
  });
</script>