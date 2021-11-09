---
title: "Contact"
weight: 5
header_menu: true
---

<!-- 
Data Handling and Business Services, Computational Studies

{{<icon class="fa fa-envelope">}}&nbsp;[alex@kalixolabs.com](mailto:alex@kalixolabs.com)


Design and Optimization, Computational Studies, Wet Lab Consulting

{{<icon class="fa fa-envelope">}}&nbsp;[kevin@kalixolabs.com](mailto:kevin@kalixolabs.com)
 -->



<!-- 
<form name="contact" method="POST" data-netlify-recaptcha="true" data-netlify="true">
  <p>
    <label> Your Name: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" /></label>
  </p>
  <p>
    <label>   Message: <textarea name="message"></textarea></label>
  </p>
    <div data-netlify-recaptcha="true"></div>
  <p>
    <button type="submit">Send</button>
  </p>
</form>
 -->



{{< rawhtml >}}
<link rel="stylesheet" href="/static/css/form.css">
<form class="cf" name="contact" method="POST" data-netlify-recaptcha="true" data-netlify="true">
  <div class="half left cf">
    <input type="text" id="input-name" placeholder="Name">
    <input type="email" id="input-email" placeholder="Email address">
    <input type="text" id="input-subject" placeholder="Subject">
  </div>
  <div class="half right cf">
    <textarea name="message" type="text" id="input-message" placeholder="Message"></textarea>
  </div>  
  <input type="submit" value="Submit" id="input-submit">
</form>
{{< /rawhtml >}}


