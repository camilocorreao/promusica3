---
title: "Ich freue mich von Ihnen zu hören!"
slug: kontakt
date: 2021-12-17T13:31:12+11:00
draft: false
weight: 40
type: contact
# google map url
gmapURL: "https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d2659.1747180709394!2d16.4011965!3d48.2032505!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x476d076a62abfdc9%3A0x8a0a299a1eb28db4!2sB%C3%B6cklinstra%C3%9Fe%20100%2C%201020%20Wien!5e0!3m2!1sde!2sat!4v1666083892017!5m2!1sde!2sat"

# contact form
form:
  title: Bitte senden Sie eine Nachricht mit Ihren Anliegen
  id: js-contactForm
  inputs:
    - id: contact-name
      col: col-md-6
      name: name
      type: text
      placeholder: Name
      minlength: 2
      required: true
      invalidFeedback: Bitte geben Sie Ihren Namen ein
    - id: contact-email
      col: col-md-6
      name: email
      type: email
      placeholder: Email Address
      required: true
      invalidFeedback: Bitte geben Sie Ihre E-Mail-Adresse ein
    - id: contact-phone
      col: col-md-6
      name: phone
      type: tel
      placeholder: Phone Number
      minlength: 8
      required: true
      invalidFeedback: Bitte Telefonnummer eingeben
    - id: contact-subject
      col: col-md-6
      name: subject
      type: text
      placeholder: Subject
      minlength: 2
      required: true
      invalidFeedback: Bitte geben Sie den Betreff der Nachricht ein
    - id: contact-message
      col: col-12
      name: message
      type: textarea
      placeholder: Message
      minlength: 6
      rows: 6
      required: true
      invalidFeedback: Bitte Nachricht eingeben.
---

You can contact us on the details below, or simply fill in the contact form to the right.
