---
layout: page
title: Kontakt
permalink: /kontakt/
published: true
---

Vi finns också på [Facebook](https://www.facebook.com/Vittra-543481875853831/) där vi ibland släpper nytt material eller skriver nyheter.

För att kontakta oss, skicka oss ett mail så hör vi av oss snarast möjligt!

<form id="formaction" class="form-horizontal" method="POST">
<fieldset>
  <div class="form-group">
    <input style="width: 200px;" type="text" name="name" placeholder="Ditt namn">
  </div>
  <div class="form-group">
    <input style="width: 200px;" type="email" name="_replyto" placeholder="Din email address">
  </div>
  <div class="form-group">
    <textarea style="width: 100%;height:300px" class="form-control" id="textarea" name="message">Ditt meddelande</textarea>
  </div>
  <div class="form-group">
    <input type="submit" value="Send">
  </div>
    <input type="text" name="_gotcha" style="display:none" />
    <input type="hidden" name="_next" value="/l"/>
</fieldset>
</form>

<script>
    var contactform =  document.getElementById('formaction');
    contactform.setAttribute('action', '//formspree.io/' + 'vittrafolkmusik' + '@' + 'gmail' + '.' + 'com');
</script>
