---
# An instance of the Contact widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: contact

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true
<!-- Calendly inline widget begin -->
<div class="calendly-inline-widget" 
data-url="https://calendly.com/sahadalhassan"
 style="min-width:320px;
 height:630px;"></div>
<script type="text/javascript"
 src="https://assets.calendly.com/assets/external/widget.js" async></script>
<!-- Calendly inline widget end -->
  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: true

design:
  columns: "2"
---
