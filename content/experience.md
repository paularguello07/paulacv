---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      title: Education
      username: admin
    design:
      css_class: centrado
      style: 'text-align: center;'
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: admin
    design:
      show_skill_percentage: true
  - block: resume-languages
    content:
      title: Languages
      username: admin
      button:
        text: Download CV
        url: uploads/resume.pdf

  - block: resume-awards
    content:
      title: Awards
      username: admin
---
