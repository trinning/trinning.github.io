---
layout: page
title: Kontakt
permalink: /kontakt/
published: true
---

Vi finns också på [Facebook](https://www.facebook.com/trinningfolk/) där vi ibland släpper nytt material eller skriver nyheter.

För att kontakta oss, fyll i ditt namn, email, och ditt meddelande så hör vi av oss så fort vi kan!

<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="contact form example">
	<!-- <title>Contact Form Example</title> -->
  </head>

  <body>

	<!-- START HERE -->

	<link rel="stylesheet" href="https://unpkg.com/purecss@1.0.0/build/pure-min.css">

	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css">
	<!-- Style The Contact Form How Ever You Prefer -->

	<form class="gform pure-form pure-form-aligned" method="POST" data-email="example@email.net"
		  action="https://script.google.com/macros/s/AKfycbze3FOPEbjqNTEIsx8T4GiEZ2YpF6ygBbmeM_qo/exec">
	  <!-- change the form action to your script url -->
        <!--input id must be honeypot or else it wont work-->
  <label class="sr-only">Keep this field blank</label>
  <input id="honeypot" type="text" name="honeypot" value="" />
  <!--the rest of your form-->
<div class="form-elements">

	  <fieldset class="pure-group">
		<label for="text">Namn:</label>
		<input type="text" class="pure-input-1" id="name" name="name" placeholder="Namn" autocomplete="off">
		<label for="email">Email Address:</label>
		<input type="email" class="pure-input-1" id="email" name="email" value="" placeholder="Email" autocomplete="off" required>
		<span class="email-invalid" style="display:none">
		  Must be a valid email address</span>
	  </fieldset>

	  <fieldset class="pure-group">
		<textarea class="pure-input-1" id="message" name="message" rows="15" placeholder="Meddelande"></textarea>
	  </fieldset>

	  <fieldset class="pure-group">
		<button type="submit" class="pure-button pure-input-1 pure-button-primary">Skicka meddelande</button>
	  </fieldset>
</div>
	  <!-- Customise the Thankyou Message People See when they submit the form: -->
	  <div class="thankyou_message" style="display:none;">
		<h3>Tack för din meddelande!</h3>
		<p><em>Vi kommer att kontakta dig på angedd mailaddress så snart vi kan.</em></p>
	  </div>
	</form>



	<!-- Submit the Form to Google Using "AJAX" -->
	<script data-cfasync="false" src="/assets/js/form-submission-handler.js">
	</script>

	<!-- END -->

  </body>
</html>

