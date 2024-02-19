---
title: 'OpenProductions'
date: 2024-02-17
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: ESG Reports from your financial bookkeeping
      text: ☀️ Open-source, trustworthy, transparent AI  ☀️
      primary_action:
        text: Get in touch
        url: https://reprex.nl/contact/
        icon: rocket-launch
      secondary_action:
        text: Our methodology
        url: https://reprex.nl/project/openproductions/
      announcement:
        text: "Meet us on the 2024 Berlinale"
        link:
          text: "Link up"
          url: "https://www.linkedin.com/in/daniel-deak/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: ESRS_dim.webp
          filters:
            brightness: 0.7
  - block: stats
    content:
      items:
        - statistic: "E"
          description: |
            Environment 
            beyond CO2 biodiversity,
            H2O, waste, recycling
        - statistic: "S"
          description: |
            Social impacts, 
            health, gender
        - statistic: "G"
          description: |
            Governance, rights 
            management, disclosures
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: features
    content:
      title: Features
      text: AI with the ESG expert in the loop
      items:
        - name: ESG
          icon: globe-europe-africa
          description: GRI & ESRS for economic, environmental and social impacts.
        - name: Cost Analysis
          icon: currency-euro
          description: Super fast page load with Tailwind CSS and super fast site building with Hugo.
        - name: Rights Management
          icon: hero/lock-open
          description: Optional rights management for future proof documentation of copyrights (music, artworks, etc.)
        - name: Knowledge base
          icon: light-bulb
          description: "Open AI: Machine-readable encoding of film (post-)production procedures budgeting, cost control and ESG impact measurement."
        - name: Human-in-the-loop AI
          icon: hero/user-plus
          description: No black-box machine learning. All algorithms are supervised by certified accountants, sustainability managers, music and art supervisors.
        - name: Futureproof
          icon: hero/calendar-days
          description: Open source (OWL/RDF) knowledge base interoperable with global libraries, open science repositories, authority data warehouses.
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Report your ESG impacts
          text: Start with CO2, add H2O, waste, pollution.
          feature_icon: check
          features:
            - "Focus on material impacts, leave out immaterial details"
            - "Use benchmarks, analyse scenarios, balance costs/benefits"
            - "Future-proof - no tie-in to ERP or bookkeeping applications, CO2 calculators, licenses."
          # Upload image to `assets/media/` and reference the filename here
          image: Slide4.webp
          button:
            text: Let's talk
            url: https://reprex.nl/contact/
        - title: Open Knowledge Base
          text: Open knowledge base for scientific and assurance audit.
          feature_icon: wifi
          features:
            - "Transparent for certified reviewers and auditors"
            - "Our solution is in regulatory sandbox"
            - "Easily extended to local requirements, practices, regulations"
            - "Follows EBU dataspace recommendations"
          # Upload image to `assets/media/` and reference the filename here
          image: Slide7.webp
          button:
            text: Join Dataspace
            url: https://reprex.nl/contact/
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: cta-card
    content:
      title: Connect your production cost reports to ESG reporting
      text: Ask for a demonstration
      button:
        text: Get in touch
        url: https://reprex.nl/contact/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
