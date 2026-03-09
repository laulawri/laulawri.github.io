---
title: "News and Media"
date: 2026-03-06
# Use the landing page type so we can add sections
# (mirror the structure of `projects.md` and `news.md`)
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    content:
      title: "News Stories"
      text: "A selection of articles, interviews and other media coverage."
      filters:
        folders:
          - media
    design:
      view: date-title-summary
      fill_image: false
      columns: 3
---
