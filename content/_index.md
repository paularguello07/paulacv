---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:

  - block: resume-biography
    content:
      # The user's folder name in `content/authors/`
      username: admin
      # Show a call-to-action button under your biography? (optional)
      # To link to a file, upload it to your `static/uploads/` folder
      button:
        text: Download CV
        url: uploads/resume.pdf
        
  
    design:
      css_class: custom-block, centrado
      css_style : centrado
      banner:
        # Upload a cover image to `assets/media/` folder and reference its filename here (optional)
        filename: ''
      biography:
        # Customize the CSS style of your biography text (optional)
        style: ''
      banner:
        filename: 'banner.jpg'


  - block: collection
    id: papers
    content:
      
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      css_class: custom-block 
      view: article-grid
      columns: 2

  - block: collection
    id: projects
    content:
      title: Selected Projects
      text: I enjoy making things. Here are a selection of projects that I have worked on over the years.
      filters:
        folders:
          - project
    design:
      css_class: custom-block 
      view: article-grid
      fill_image: false
      columns: 3

    
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      css_class: custom-block 
      view: community/citation



  - block: resume-awards
    content:
      title: Awards
      # Note: `username` refers to the user's folder name in `content/authors/`
      username: admin
    design:
      css_class: custom-block 

---
