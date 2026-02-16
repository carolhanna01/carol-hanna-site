---
title: 'From Kotlin to Swift and Back: Toward Fully Automated Cross-Language Code Transpilation'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Sachi Lad
  - Carol Hanna
  - Justyna Petke

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

# date: '2025-07-28'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-01-19'


# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In International Conference on Automated Software Engineering Workshops (ASEW)
# publication_short: Under Review

abstract: Mobile platforms dominate software development, yet transpiling code between Kotlin (Android) and Swift (iOS) remains a major challenge. This task is essential for cross-platform accessibility, particularly when porting iOS apps to Android. Despite its importance, research on Kotlin-Swift transpilation and particularly, fixing these transpilation bugs is scarce. We thus present the first large-scale study of Kotlin-Swift transpilation bugs. We identify 149 real-world bugs, introduce a taxonomy of common bug types, and propose new mutation operators to address them. Combined with existing operators, our proposed operators have potential to fix 101 of these bugs. Building on the taxonomy of transpilation bugs and the mutation operators we develop to repair them, we lay out a research agenda for reliable, fully-automated, end-to-end software transpilation workflows for the mobile domain.

tags:
  - Code Transpilation
  - Mobile

# Display this page in the Featured widget?
# featured: true

# Standard identifiers for auto-linking
hugoblox:
  # ids:
  #   doi: 10.5555/123456

# Custom links
links:
  - type: paper
    label: Paper
    url: "https://ieeexplore.ieee.org/abstract/document/11334682"
  # - type: code
  #   url: https://github.com/HugoBlox/kit
  # - type: dataset
  #   url: https://github.com/HugoBlox/kit
  # - type: slides
  #   url: https://www.slideshare.net/
  # - type: source
  #   url: https://github.com/HugoBlox/kit
  # - type: video
  #   url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
