---
# An instance of the Experience widget.
# Documentation: https://docs.hugoblox.com/page-builder/
widget: experience

id: education

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

title: Education
subtitle:

# Date format for experience
#   Refer to https://docs.hugoblox.com/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: BSc Computer Science & Engineering
    company: BRAC University; CGPA 3.99
    company_url: 'https://www.bracu.ac.bd/'
    company_logo: brac_uni
    location: Dhaka, Bangladesh
    date_start: '2018-08-01'
    date_end: '2022-04-30'
    
  - title: SSC
    company: Notredame College; GPA 5.0
    company_url: 'https://ndc.edu.bd/'
    company_logo: notredame_logo
    location: California
    date_start: '2015-08-01'
    date_end: '2017-08-01'

design:
  columns: '1'

advanced:
  css_class: "education-section"
---
