---
title: 'Contact'
layout: 'layouts/page.html'
custom_css: 'footer {visibility: visible; font-size:2rem; font-weight:400;} div p {font-size:2rem;font-family: Roboto}'
---

<div id="grid">
  <div>
  Ellermanstraat 33,  <br>
  2060 Antwerpen  <br>
  +03 220 33 00
  <br><br><br>
  hello@mathieuatwork.be
  <br><br>
  <a id="mail" href="mailto:hello@mathieuatwork.be">Stuur mij een e-mail!<a>
  </div>
  <br>
  <br>
  <form action="/action_page.php">
      <label for="fname">Voornaam</label>
      <br><input type="text" id="fname" name="firstname" placeholder="Uw naam..">
      <br>
      <br><label for="lname">Achternaam</label>
      <br><input type="text" id="lname" name="lastname" placeholder="Uw achternaam..">
      <br>
      <br><label for="subject">Onderwerp</label>
      <br><textarea id="subject" name="Your message" placeholder="Typ hier uw bericht.." style="height:200px"></textarea>
      <br><input type="submit" value="Verstuur bericht">
  </form>
</div>
