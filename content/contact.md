title: "Contact Me"
date: 2025-03-15
type: landing
  menu:
  main:
    weight: 50  # Matches the navigation order


sections:
  - block: contact
    content:
      title: "Get in Touch"
      text: "Feel free to reach out for collaborations, opportunities, or just to say hi!"
      email: "your.email@example.com"  # Replace with your email
      phone: "+1 (123) 456-7890"  # Optional
      address: "Your City, Country"  # Optional
      show_social: true  # Displays social media links if configured
      form: true  # Enables the contact form

    design:
      show_border: false
      show_background: false

  - block: map
    content:
      title: "Find Me Here"
      text: "Here’s my location on the map."
      map:
        provider: google  # Supports 'google' or 'openstreetmap'
        lat: 43.002316  # Replace with your latitude
        lon: -89.424095  # Replace with your longitude
        zoom: 15  # Adjust zoom level

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
