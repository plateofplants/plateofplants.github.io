---
layout: default

title: Contact
---

<form action="//formspree.io/hannah@plateofplants.com" method="POST" class="contact form">
  <fieldset>
    <legend>Let's get in touch.</legend>
    <input type="text" name="name" placeholder="Your Name" />
    <input type="email" name="_replyto" placeholder="Your Email" />
    <textarea name="message" rows="5" placeholder="Message"></textarea>
    <input type="hidden" name="_next" value="{{ "/thank-you-for-contacting-me" | prepend: site.baseurl | prepend: site.url }}" />
    <input type="hidden" name="_subject" value="Plate of Plants - New Contact" />
    <input type="text" name="_gotcha" style="display:none" />
  </fieldset>
  <input type="submit" value="Send">
</form>
