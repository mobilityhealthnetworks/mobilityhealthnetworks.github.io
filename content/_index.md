---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero-with-stats
    content:
      title: The Science of Connections
      text: "**Urban Mobility and Health Network**"
      details: "June 02, 2025. \n\n[NetSci 2025](https://netsci2025.github.io/) Maastricht, Netherlands"
      # primary_action:
      #   text: Submit your abstract
      #   url: https://forms.gle/X7VgEFRWQaEvxVTw9
      #   icon: pencil-square
      items:
        - name: "Sessions"
          description: "6 (2 keynotes, 1 panel, 3 short talks)"
        - name: "Attendees"
          description: "20+"
        - name: "Venue"
          description: "[FPN Tongeren zaal](https://maps.app.goo.gl/BJ6aLFSEL2VH51Lk9)"
        - name: "Location"
          description: "Faculty of Psychology and Neuroscience (FPN): Universiteitssingel 40, 6229 ER Maastricht"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "bg-gradient-to-r from-rose-100 to-teal-100"
#      background:
#        color: ""
#        image:
#          # Add your image background to `assets/media/`.
#          filename: ""
#          filters:
#            brightness: 1.0
  - block: countdown
    content:
      title: "Workshop live on"
      text: "June 02, 2025"
      text_after: "Submit your abstract [here](https://forms.gle/X7VgEFRWQaEvxVTw9)"
      date: '2025-06-02 00:00:01'
    design:
      # Section background color (CSS class)
      css_class: "bg-primary-500"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]

  - block: markdown
    id: about
    content:
      title: "About the conference"
      text: "Infectious disease modelling increasingly depends on contact matrices and networks to capture the intricate dynamics of pathogen transmission. These tools provide critical insights into the “who-is-in-contact-with-whom” paradigm, enabling more precise simulations of close-contact infectious diseases. To achieve this, epidemiologists and public health researchers are keen to simulate mobility networks with high spatiotemporal granularity. \nIn a parallel universe, travel demand modelers and urban planners focus on simulating urban mobility patterns with social networks, albeit with distinct objectives. Their efforts primarily aim at ex-ante evaluations of transport interventions to optimize infrastructure and operational decisions. Recent advancements in integrating large-scale transit smart card data and cellular trace data with survey datasets offer unprecedented opportunities to create high-fidelity digital twins of complex urban systems. These advancements hold significant potential for informing infectious disease modelling by providing epidemiologists with mobility networks that can represent nitty-gritties of urban systems. \nThis workshop will serve as an interdisciplinary platform at the intersection of Urban Mobility, Health, and Network Science. By fostering collaboration between travel demand modelers, social network scientists, and epidemiologists, the workshop aims to start dialogue about leveraging digital twin developed by travel demand modellers in infectious disease models to support informed public health interventions in complex urban systems."
          
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: people
    id: speakers
    content:
      title: Keynote Speakers
      text: ""
      user_groups: ['Keynote Speakers']
    design:
      show_role: true
      show_social: true
      show_interests: false
  - block: people
    id: organizers
    content:
      title: Organizers
      text: ""
      user_groups: ['Organizers']
    design:
      show_role: true
      show_social: true
      show_interests: false
  - block: markdown
    id: agenda
    content:
      title: Agenda
      text: |
        **DAY**
        {style="padding-top: 2rem"}
        {{< table path="schedule.csv" header="true" >}}
  # - block: testimonials
  #   content:
  #     title: ""
  #     text: ""
  #     items:
  #       - name: "Alice Smith"
  #         role: "Researcher at X"
  #         # Upload image to `assets/media/` and reference the filename here
  #         image: "testimonial-1.jpg"
  #         text: "It has to be the most insightful conference I've ever attended!"
  #   design:
  #     spacing:
  #       # Reduce bottom spacing so the testimonial appears vertically centered between sections
  #       padding: ["6rem", 0, 0, 0]
  - block: logos
    content:
      title: "Sponsors Making This Possible"
      text: "Thanks to the following sponsors for making this incredible event possible!"
      # Image path relative to assets/media/ folder
      logo_folder: 'sponsors/'
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
  # - block: newsletter
  #   content:
  #     title: "Stay up to date"
  #     text: "Be the first to receive conference updates such as added speakers, deadlines, and ticket deals."
  #     text_cta: "Sign up to our newsletter 🔥"
  #     button:
  #       text: "Subscribe"
  #     convertkit:
  #       form_id: ''
  #       msg_subscribed: "Success! Please check your email to confirm your subscription."
  #   design:
  #     card:
  #       # Card background color (CSS class)
  #       css_class: "bg-primary-700"
  #       css_style: ""
---
