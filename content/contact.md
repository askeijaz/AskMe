---
title: "Contact"
layout: "single"
slug: "contact"
no_comments: true
---

<!-- modify this form HTML and place wherever you want your form -->

<form action="https://formspree.io/f/{{ .Site.Params.formspree_id }}" method="POST">    
<p class="mb-4">Thank you for your interest in getting in touch with us. Please send your message here. We will reply as soon as possible!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Name*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-mail Address*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Message*" required></textarea>    
<input class="btn btn-dark" type="submit" value="Send">
</form>