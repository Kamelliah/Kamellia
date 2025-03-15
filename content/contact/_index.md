---
title: "Contact Me"
date: 2025-03-15
type: landing
menu:
  main:
    weight: 50  # Controls menu order

sections:
  - block: contact
    content:
      title: "Get in Touch"
      text: "Feel free to reach out for collaborations, opportunities, or just to say hi!"
      email: "your.email@example.com"
      phone: "+1 (123) 456-7890"
      address: "Your City, Country"
      show_social: true
      form: true

  - block: map
    content:
      title: "Find Me Here"
      text: "Here’s my location on the map."
      map:
        provider: google
        lat: 43.002316
        lon: -89.424095
        zoom: 15

  - block: hours
    content:
      title: "Hours of Operation"
      text: "Available for inquiries during these hours."
      schedule:
        - day: "Monday - Friday"
          time: "9:00 AM - 3:00 PM"
        - day: "Saturday"
          time: "Closed"
        - day: "Sunday"
          time: "Closed"


