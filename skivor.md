---
layout: category
title: Vår skiva
permalink: /skivor/
published: true
---

Vi är mycket stolta att efter ett par decenniers spelande tillsammans presentera vår första skiva.

Läs gärna [Liras recension](http://www.lira.se/skivrecension/steg/) där vi bland annat fick omdömet _"Finurligt leker de tre Zorn­märkesbelönade spelkvinnorna med intressanta harmonier och finfint stämspel. Lätt är att drömma sig bort till deras sommarlandskap med blå himmel, gröna ängar och gula rapsfält"_.

Skivan finns till försäljning för 120 kronor och vill du köpa ett (eller flera!) exemplar så fyll i formuläret nedan. Du kan också [kontakta oss](/kontakt) på andra sätt om du har speciella önskemål.

<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="contact form example">
	<!-- <title>Contact Form Example</title> -->
  </head>

  <body>
	<h2 class="content-head is-center">Beställningsformulär</h2>
	<aside>
      <p>
        Fyll i ditt namn, email, din address och hur många skivor du vill ha
		så kommer skivan tillsammans med en faktura på posten!
      </p>
	</aside>

	<!-- START HERE -->

	<link rel="stylesheet" href="https://unpkg.com/purecss@1.0.0/build/pure-min.css">
	<!--[if lte IE 8]>
		<link rel="stylesheet" href="https://unpkg.com/purecss@1.0.0/build/grids-responsive-old-ie-min.css">
		<![endif]-->
	<!--[if gt IE 8]><!-->
		<link rel="stylesheet" href="https://unpkg.com/purecss@1.0.0/build/grids-responsive-min.css">
		<!--<![endif]-->

		<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css">
		<!-- Style The Contact Form How Ever You Prefer -->
		<link rel="stylesheet" href="/assets/css/pure.css">

		<div class='pure-g'>
		  <div class='pure-u-1 pure-u-lg-12-24'>
			<form class="gform pure-form pure-form-aligned" method="POST" data-email="example@email.net"
				  action="https://script.google.com/macros/s/AKfycbxdvyw5YFs5V2Lx7WcymJ_JMvC-bEBhNbyA4I3HUVfEXGrlG3Tt/exec">
			  <!-- change the form action to your script url -->
			  <fieldset class="pure-group">
				<label for="text">Namn:</label>
				<input type="text" class="pure-input-1" id="first_name" name="first_name" placeholder="Förnamn" autocomplete="off">
				<input type="text" class="pure-input-1" id="last_name" name="last_name" placeholder="Efternamn" autocomplete="off">
			  </fieldset>

			  <fieldset class="pure-group">
				<label for="text">Address: </label>
				<input type="text" class="pure-input-1" id="address" name="address" placeholder="Gata" autocomplete="off">
				<input type="text" class="pure-input-1" id="postnummer" name="postnummer" placeholder="Postnummer" autocomplete="off">
				<input type="text" class="pure-input-1" id="postort" name="postort" placeholder="Postort" autocomplete="off">
			  </fieldset>

			  <fieldset class="pure-group">
				<label for="number">Antal skivor:</label>
				<input type="number" class="pure-input-1" id="antal_skivor"  name="antal_skivor" min="1" value="1">
			  </fieldset>

			  <fieldset class="pure-group">
				<label for="email">Email Address:</label>
				<input type="email" class="pure-input-1" id="email" name="email" value="" placeholder="Email" autocomplete="off" required>
				<span class="email-invalid" style="display:none">
				  Must be a valid email address</span>
			  </fieldset>

			  <fieldset class="pure-group">
				<textarea class="pure-input-1" id="message" name="message" placeholder="Eventuella kommentarer"></textarea>
			  </fieldset>

			  <fieldset class="pure-group">
				<button type="submit" class="pure-button pure-input-1 pure-button-primary">Skicka beställning</button>
			  </fieldset>

			  <!-- Customise the Thankyou Message People See when they submit the form: -->
			  <div class="thankyou_message" style="display:none;">
				<h3>Tack för din beställning!</h3>
				<h4>Vi skickar en bekäftelse så snart vi kan.<br>
				  Skivan kommer på posten	tillsammans med faktura.<br>
				  Är något oklart kommer vi att kontakta dig på angedd mailaddress.</h4>
			  </div>

			</form>
		  </div>
		  <div class='pure-u-0 pure-u-lg-1-24'>
		  </div>
		  <div class='pure-u-0 pure-u-lg-11-24 bottom'>
			<img src="/assets/trinning-steg-framsida_600x526.jpg" alt="Steg">
		  </div>
		</div>



		<!-- Submit the Form to Google Using "AJAX" -->
		<script data-cfasync="false" src="/assets/js/form-submission-handler.js">
		</script>

		<!-- END -->

  </body>
</html>

