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
  email: yan.shi@utah.edu
  address:
    street: Room 2930, Languages & Communication Bldg, 255 S Central Campus Dr.  
    city: Salt Lake City
    region: UT
    postcode: '84102'
    country: United States
    country_code: US
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: Enter Building and take the stairs to Office 2930 on Floor 2
  office_hours:
    - 'Monday 10:00 to 11:00'
    - 'Wednesday 09:00 to 10:00'
  appointment_url: 
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 

design:
  columns: '2'
---
