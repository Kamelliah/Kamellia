---
title: "Contact Me"
date: 2025-03-15
type: landing
layout: page
menu:
  main:
    weight: 50

sections:
  - block: hero  # Using 'hero' instead of 'contact' or 'form'
    content:
      title: "Get in Touch"
      text: "Feel free to reach out for collaborations, opportunities, or just to say hi!"
      button:
        text: "Email Me"
        url: "mailto:your.email@example.com"

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


