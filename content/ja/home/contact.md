---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: アクセス
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

#   # Email form provider
#   form:
#     provider: netlify
#     formspree:
#       id:
#     netlify:
#       # Enable CAPTCHA challenge to reduce spam?
#       captcha: false

  # Contact details (edit or remove options as required)
  email: 
  phone: +81-6-6105-6074
  address:
    street: 山田丘2-8
    city: 吹田市
    region: 大阪府
    postcode: '565-0871'
    country: Japan
    country_code: JP
  coordinates:
    latitude: '34.820899'
    longitude: '135.523181'
  directions: テクノアライアンスC棟のエレベータで5階C503にお越しください
  office_hours:
    - '9:00 - 17:00'
#   appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/ids_ou'
    # - icon: video
    #   icon_pack: fas
    #   name: Zoom Me
    #   link: 'https://zoom.com'

design:
  columns: '2'
---