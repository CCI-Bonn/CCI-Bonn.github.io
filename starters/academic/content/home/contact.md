---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle: We are always seeking new academic and industry collaboration partners. Feel free to reach out to us at contact@ccibonn.ai. 

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
  email: contact@ccibonn.ai
  address:
    street: 'Bonnjour 1.0G, Baunscheidtstraße 17' 
    city: Bonn
    postcode: '53113'
    country: Germany
    country_code: DE
  #post_address: 'Postbox: University Hospital Bonn, Venusberg-Campus 1, Building C81, 53127 Bonn, Germany'
  coordinates:
    latitude: '50.695805'
    longitude: '7.103828'

design:
  columns: '2'
---
