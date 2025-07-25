---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Télécharger mon CV
        url: https://elvipy.github.io/pierrick-levourch/uploads/cv_fr.pdf
    design:
      css_class: dark
      background:
        color: indigo
        #image:
          # Add your image background to `assets/media/`.
          #filename: stacked-peaks.svg
          #filters:
          #  brightness: 1.0
          #size: cover
          #position: center
          #parallax: false
  - block: collection
    content:
      title: Publications
      text: ""
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: article-grid
      columns: 1
      background:
        color: indigo
  - block: collection
    id: exposes
    content:
      title: Exposés
      filters:
        folders:
          - exposes
    design:
      view: article-grid
      columns: 1
      background:
        color: indigo
#  - block: contact
#    id: contact
#    content:
#      title: Contact
#      email: pierrick.le-vourc-h@umontpellier.fr
#      address: 
#        street: Place Eugène Bataillon
#        city: Montpellier
#        postcode: '34090'
#        country: France
#      directions: Entrer dans le bâtiment 9 et trouver le bureau 130 au premier étage.
#      coordinates:
#        latitude: 43.63117878118292
#        longitude: 3.8663403106686034
#      autolink: true
#    design:
#      colums: '2'
---
