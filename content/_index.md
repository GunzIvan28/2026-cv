---
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/Ivan_Sserwadda_resume.docx
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: markdown
    content:
      title: 'Research Focus'
      subtitle: ''
      text: |-
        I develop and apply reproducible bioinformatics workflows for infectious disease genomics, antimicrobial resistance, metagenomics, and public health surveillance.

        My work spans high-throughput sequencing analysis for HIV, tuberculosis, malaria, SARS-CoV-2, cancer, bacterial pathogens, and environmental metagenomics, with a focus on capacity building and open-source tools for African genomics and global health.

        I teach and mentor in Python, Biopython, sequence analysis, phylogenetics, microbiome analysis, and NGS data interpretation.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Oral and Poster Presentations
      filters:
        folders:
          - events
    design:
      view: card
  - block: collection
    id: news
    content:
      title: Community and Professional Activities
      subtitle: ''
      text: ''
      page_type: blog
      count: 10
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      offset: 0
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]
---
