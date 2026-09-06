---
layout: single
permalink: /jointhegoteam/
title: "Join the Go Team!"
author_profile: true
---

## How to join
Thank you for your interest in furthering the gospel through this ministry.<br>

>**Romans 10:15**\
How beautiful are the feet of those who preach the gospel of peace, who bring glad tidings of good things!

{% capture statementlink %}
Let us agree to bring the news of Jesus Christ and Him crucified in unity of the essentials of faith.<br>
* Please take a moment to read the Statement of Faith on this site and understand its doctrinally significance. If any of these doctrines are unfamiliar or contrary to your own, let us discuss them and pray for common understanding.
{% endcapture %}

<div class="notice--info">
  <h4 class="no_toc">One body, one Spirit, one hope, one Lord, one faith, one baptism, one God and Father</h4>
  {{ statementlink | markdownify }}
</div>

<a href="/statementoffaith/" target="_blank" class="btn btn--info">Statement of Faith</a>

## Testimony and Information
Please keep your testimony within 5-10 sentences total.<br>

<b>Before Jesus</b> What was  your life like before coming to Jesus?<br>
<b>Meeting Jesus</b> Who brought you to Jesus? How did your circumstances change?<br>
<b>After Jesus</b> What is your life like now? How has life changed since coming to Jesus?<br>

<form name="gformjoingo" id="gformjoingo" enctype="text/plain" action="https://docs.google.com/forms/d/e/1FAIpQLSfwJqQt_s8wgBBbaAUrLrzfURXEIcYozZYamWbfIu1lMwgUhQ/formResponse?" target="hidden_iframejoingo" onsubmit="submitted=true;">
  <fieldset>
    Name: <input type="text" size="30" name="entry.812009993"><br>
	Contact Preference(s): <input type="text" size="30" name="entry.2113411518"><br>
	Testimony: <textarea name="entry.1115827369"></textarea>
	<input type="submit" name='submit' value="Submit">
  </fieldset>
</form>

<iframe name="hidden_iframejoingo" id="hidden_iframejoingo" style="display:none;" onload="if(submitted) {}"></iframe>

<script src="/assets/js/main.min.js"></script>
<script type="text/javascript">var submitted=false;</script>
<script type="text/javascript">
  $('#gformjoingo').on('submit', function(e) {
  $('#gformjoingo *').fadeOut(2000);
  $('#gformjoingo').prepend('Thank you for your willingness to be the feet of Jesus.');
  });
</script>