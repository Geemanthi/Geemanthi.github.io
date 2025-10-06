---
# title: Publications
# cms_exclude: true

# # View.
# view: citation
      
# # Optional header image (relative to `static/media/` folder).
# banner:
#   caption: ''
#   image: ''

title: 'Publications'
date: 2024-05-19
type: landing
cms_exclude: true
design:
  # Section spacing
  spacing: '5rem'

sections:
  - block: collection
    content:
     title: Publications
     text: ''
     filters:
       folders:
         - publication
       exclude_featured: false
     count: 30
    design:
     view: citation
  - block: markdown
    content:
      title: In Development
      text: |
        
        - A Framework for Computational Fluid Dynamics Investigations of Moving Objects using Ansys Fluent.
        - Review of Flapping Wing Bioinspired Aerial Vehicles: From Theories to Applications.
        - Design and Development of a Vehicle-Mounted Test Apparatus for Investigating the Aerodynamic Performance of UAV Components.

      
    design:
      columns: "1"
      background:
        text_color_light: true
  - block: collection
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2

---
