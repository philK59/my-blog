---
title: "Contact"
date: 2021-05-27T18:36:18+02:00
draft: false
---

<form action="/thankyou" method="post" name="Contact" data-netlify="true" netlify-honeypot="bot-field" netlify>
    <p style="visibility: hidden">
        <label> Don't Fill This Out If You're Human:" </label><input name=bot-field/>
    </p>
    <label for="fname">Nom</label>
    <br>
    <input type="text" id="fname" name="firstname" placeholder="Votre nom..">
    <br>
    <br>
    <label for="lname">Prénom</label>
    <br>
    <input type="text" id="lname" name="lastname" placeholder="Votre prénom..">
    <br>
    <br>
    <label for="email">Email</label>
    <br>
    <input type="text" id="email" name="email" placeholder="email@example.com">
    <br>
    <br>
    <label for="message">Message</label>
    <br>
    <textarea id="message" name="message" placeholder="Décrivez-nous votre projet en quelques mots" style="height: 200px"></textarea>
    <br>
    <br>
    <div data-netlify-recaptcha></div>
    <br>
    <br>
    <input type="submit" value="Submit" style="">
</form>
