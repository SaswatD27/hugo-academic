---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true
  
  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: saswat.das@niser.ac.in
  phone: +91 63701 47889
  address:
    street: NISER Campus
    city: Bhubaneswar
    region: Odisha
    postcode: '742050'
    country: India
    country_code: IN
  #coordinates:
    #latitude: '37.4275'
    #longitude: '-122.1697'
  directions: Enter the SMS Building and go down the left hall of the ground floor
  office_hours:
    - 'Monday 16:30 to 18:00'
    - 'Wednesday 16:30 to 18:00'
    - 'Friday 13:30 to 17:30'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/SaswatDas19'
    - icon: fa-brands fa-linkedin
      icon_pack: fab
      name: Connect with Me
      link: 'https://www.linkedin.com/in/saswat-das-3b7051179/'

design:
  columns: '2'
---
