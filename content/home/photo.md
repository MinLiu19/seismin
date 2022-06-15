---
# An instance of the Contact widget.
widget: photo

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 140

title: Photo
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
  email: m.liu@dal.ca
  phone: +1 902 499 0104
  address:
    street: 26 Carrie Best Crt
    city: Halifax
    region: NS
    country: Canada


design:
  columns: '2'
---
