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
#    provider: netlify
    provider: formspree
    formspree:
      id: xnqoylgb
      captcha: true
      captcha_key: 6Lel-uIdAAAAAFxCgi3qQgszGtibPnS9Eoc8YGMF
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
#  email: 'dbader13@gmail.com'
#  phone: '973-596-6340'
  address:
    street: 'Institute for Data Science, New Jersey Institute of Technology, 101 Hudson St., Suite 3610'
    city: 'Jersey City'
    region: NJ
    postcode: '07302'
    country: United States
    country_code: US
  coordinates:
    latitude: '40.7161'
    longitude: '-74.0344'
#  directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
#  office_hours:
#    - 'Monday 10:00 to 13:00'
#    - 'Wednesday 09:00 to 10:00'
#  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Prof_DavidBader'
#    - icon: video
#      icon_pack: fas
#      name: Zoom Me
#      link: 'https://zoom.com'
    - icon: keybase
      icon_pack: fab
      name: Chat on Keybase
      link: 'https://keybase.io/dbader13'

design:
  columns: '2'
---
