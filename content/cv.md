---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`
# button:
#   text: Download CV
#   url: uploads/resume.pdf

# Page sections
sections:  
  - block: resume-experience
    content:
      username: admin
      button:
        text: Download full CV
        url: ../uploads/CV.pdf
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: resume-skills
    content:
      title: Technical Skills
      username: admin
    design:
      show_skill_percentage: false
  - block: resume-awards
    content:
      title: Grants & Scholarships
      username: admin
  - block: resume-languages
    content:
      title: Languages
      username: admin
---
