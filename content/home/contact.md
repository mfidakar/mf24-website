---
# An instance of the Contact widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: contact

#I put inactive the contact page for some reason, but later #the page is ready and I can activate it here
active: false

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 100

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true
  
  # Email form provider
  form:
    provider: formspree
    formspree:
      id: test
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false
  
design:
  columns: '2'
---
