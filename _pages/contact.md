---
title: Contact
layout: single
permalink: /contact/
classes: wide
---

## Formulaire de contact
<!-- modify this form HTML and place wherever you want your form -->

<form id="fs-frm" name="survey-form" accept-charset="utf-8" action="https://formspree.io/f/myyqkywb" method="post">
  <fieldset id="fs-frm-inputs">
    <label for="full-name">Nom complet * </label>
    <input type="text" name="name" id="full-name" placeholder="NOM et Prénom" required="true">
    <label for="full-name">Âge de l'apprenant * </label>
    <input type="text" name="age" id="age" placeholder="Âge" required="true">
    <label for="email-address">Courriel *</label>    
    <input type="email" name="_replyto" id="email-address" placeholder="courriel@domain.xyz" required="true">
    <label for="telephone">Téléphone *</label>
    <input type="telephone" name="telephone" id="telephone" placeholder="06 01 02 03 04">
    <fieldset id="fs-frm-selects">
      <label for="timely">Vous souhaitez des leçons d'apprentissage :</label>
      <select name="timely" id="timely" required="">
        <option value="" selected="" disabled="">Préciser le type de leçons souhaitées</option>
        <option value="1">Nataqua' Safe</option>
        <option value="2">Nataqua' Junior</option>
        <option value="3">Nataqua' Senior</option>
      </select>
      <label for="timely">Vous souhaitez un cours thématique :</label>
      <select name="quality" id="quality" required="">
        <option value="" selected="" disabled="">Préciser votre programme</option>
        <option value="4">Nataqua' Perf</option>
        <option value="5">Nataqua' Rescue</option>
        <option value="6">Nataqua' Bac</option>
        <option value="7">Nataqua' Gym</option>
        <option value="8">Nataqua' Santé</option>
        <option value="9">Nataqua' Phobie</option>
        <option value="10">à la carte</option>
      </select>  
        <label for="timely">Vous demande concerne : *</label>
      <select name="quality" id="quality" required="true">
        <option value="" selected="" disabled="">Préciser le lieu</option>
        <option value="11">à domicile</option>
        <option value="12">Centre Nautique Tony Bertrand</option>
        <option value="13">Piscine Benjamin Delessert</option>
        <option value="14">Piscine Garibaldi</option>
        <option value="15">Piscine Saint Exupéry</option>
        <option value="16">Piscine de Vaise</option>
      </select>
    </fieldset>
    <label for="message">Message</label>
    <textarea rows="3" name="message" id="message" placeholder="Des précisions sur votre demande (disponibilités, niveau, prénom de l'apprenant...)" required=""></textarea>
    <input type="hidden" name="_subject" id="email-subject" value="Survey Responses">
  </fieldset>
  <input type="submit" value="Envoyer">
</form>

\* champs requis

## Nous joindre directement par courriel ou téléphone


courriel : contact(at)nataqualyon.fr

tel : 06 XX XX XX XX ou 06 XX XX XX XX