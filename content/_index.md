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
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      # Avatar customization
      avatar:
        size: medium  # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Research Experience'
      subtitle: ''
      text: |-
        As a research assistant at FAST NUCES, I am engaged in research that explores forecasting, federated learning, and vision-language applications. My work includes developing methods for multivariate time series modeling and air quality prediction, where I experiment with advanced forecasting techniques and distributed frameworks.

        In parallel, I design federated learning pipelines for multi-sensor human activity recognition, enabling robust models to train across heterogeneous datasets while preserving privacy. I am also advancing domain-aware vision-language models, improving image captioning systems with cultural and contextual relevance. Collectively, these projects aim to build trustworthy, multimodal AI systems that connect research with real-world impact.

        I am open to collaborative opportunities in research and applied AI.
    design:
      columns: '1'
  