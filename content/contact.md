---
title: "Contact Me"
date: 2025-03-15
type: landing
layout: page
menu:
  main:
    weight: 50  # Controls menu order

sections:
  - block: form  # Change from 'contact' to 'form'
    content:
      title: "Get in Touch"
      text: "Feel free to reach out for collaborations, opportunities, or just to say hi!"
      email: "your.email@example.com"
      phone: "+1 (123) 456-7890"
      address: "Your City, Country"
      show_social: true
      form: true  # Enables the contact form

    design:
      show_border: false
      show_background: false

  - block: map
    content:
      title: "Find Me Here"
      text: "Here’s my location on the map."
      map:
        provider: google
        lat: 43.002316
        lon: -89.424095
        zoom: 15

    design:
      show_border: false
      show_background: false

  - block: hours
    content:
      title: "Hours of Operation"
      text: "Available for inquiries during these hours."
      schedule:
        - "Monday - Friday: 9:00 AM - 3:00 PM"
        - "Saturday: Closed"
        - "Sunday: Closed"

    design:
      show_border: true
      show_background: false
---


