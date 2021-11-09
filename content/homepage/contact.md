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
<form name="simpleContactForm" method="POST" data-netlify="true" id="simple-contact-form" class="contact-form">
    <p class="form-row">
        <label id="contact-form-name-label" for="contact-form-name" class="form-label">Name</label>
        <input type="text" name="name" id="contact-form-name" aria-labelledby="contact-form-name-label" class="form-input" />
    </p>
    <p class="form-row">
        <label id="contact-form-email-label" for="contact-form-email" class="form-label">Email address</label>
        <input type="email" name="email" id="contact-form-email" aria-labelledby="contact-form-email-label" class="form-input" />
    </p>
    <p class="form-row">
        <label id="contact-form-message-label" for="contact-form-message" class="form-label">Message</label>
        <textarea
            name="message"
            id="contact-form-message"
            aria-labelledby="contact-form-message-label"
            class="form-textarea"
            rows="7"
        ></textarea>
    </p>
    <p class="form-row form-submit">
        <button type="submit" class="button">Send Message</button>
    </p>
</form>
{{< /rawhtml >}}


