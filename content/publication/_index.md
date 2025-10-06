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
         - publication/dabare-2024
       exclude_featured: false
     count: 30
    design:
     view: citation
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
