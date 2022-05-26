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
      captcha: true

  # Contact details (edit or remove options as required)
  email: dullecd@mail.uc.edu
  phone: (567)208-2131
  address:
    street: 2920 Woodside Drive
    city: Cincinnati
    region: OH
    postcode: '45219'
    country: United States
    country_code: US
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  # office_hours:
  #   - 'Monday 10:00 to 13:00'
  #   - 'Wednesday 09:00 to 10:00'
  # appointment_url: 'https://calendly.com'
  contact_links:
    - icon: linkedin
      icon_pack: fab
      name: Connect with me
      link: 'https://www.linkedin.com/in/chad-dulle-96074a235/'
    - icon: address-card
      icon_pack: fas
      name: Univeristy of Cincinnati Profile
      link: 'https://business.uc.edu/faculty-and-research/departments/finance/research/phd-students/chadwick-dulle.html'
    - icon: github
      icon_pack: fab
      name: GitHub Page
      link: 'https://github.com/chadwick24'
    - icon: cv
      icon_pack: ai
      name: Curriculum Vitae
      link: 'https://zoom.com'

design:
  columns: '2'
---
