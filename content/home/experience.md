---
# An instance of the Experience widget.
# Documentation: https://docs.hugoblox.com/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
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
  - title: Student Coordinator
    company: CBS Science Club
    company_url: ''
    company_logo: ''
    location: Mumbai
    area: Mumbai  # <-- This is the required fix
    date_start: '2023-02-01'
    date_end: '2025-04-30'
    description: |
      CBS Science Club is a student organization that aims to foster a healthy environment for scientific discussions. My roles include:
      * Coordinating the planning and curation of sessions and talks with researchers.
      * Managing expenses for the club's activities.
---
