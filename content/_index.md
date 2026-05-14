---
title: 'Home'
date: 2023-10-24
type: landing

design:
  background:
    image:
      # Add your image background to `assets/media/`.
      filename: bg-hue.svg

sections:
  - block: resume-biography
    content:
      # The user's folder name in content/authors/
      username: me
    design:
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: cta-button-list
    content:
      # Need a custom icon?
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      buttons:
        - text: LinkedIn
          icon: brands/linkedin
          url: https://www.linkedin.com/in/hadi-choubdar-32b81512a
        - text: Google Scholar
          icon: academicons/google-scholar
          url: https://scholar.google.com/citations?user=O05Nfd0AAAAJ&hl=en
        - text: ResearchGate
          icon: academicons/researchgate
          url: https://www.researchgate.net/
        - text: ORCID
          icon: academicons/orcid
          url: https://orcid.org/0000-0001-9609-1354
        - text: GitHub
          icon: brands/github
          url: https://github.com/hadichoubdar
        - text: X (Twitter)
          icon: brands/x-twitter
          url: https://x.com/HChoubdar
        - text: CV
          icon: academicons/cv
          url: /uploads/cv.pdf
        - text: Contact Me
          icon: hero/envelope
          url: mailto:hadi.choubdarparvin@mail.mcgill.ca
---
