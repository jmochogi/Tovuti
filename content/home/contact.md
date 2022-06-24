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
  email: jgeteregechi@ithaca.edu
  phone: 888 888 88 88
  address:
    street: 953 Danby Rd. 
    city: Ithaca
    region: NY
    postcode: '14850'
    country: United States
    country_code: US
  coordinates:
    latitude: '42.4245'
    longitude: '-76.4938'
  directions: Come to Williams Hall third floor. Faculty Offices (Door 311E)
  office_hours:
    - 'Thursday 11:30 to 13:00'
    - 'Wednesday 09:00 to 10:00'
  appointment_url: 'https://calendly.com/jmochogi/20min?month=2022-06'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: Not a fan but you can DM Me
      link: 'https://twitter.com/jmochogi'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://ithaca.zoom.us/j/3364817575?pwd=WlA1S3hJWWZNTTFoWUVaZlA1clhtdz09'

design:
  columns: '2'
---
