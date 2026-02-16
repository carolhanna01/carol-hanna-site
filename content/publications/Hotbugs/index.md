---
title: 'HotBugs. jar: A Benchmark of Hot Fixes for Time-Critical Bugs'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Carol Hanna
  - Federica Sarro
  - Mark Harman
  - Justyna Petke

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

# date: '2025-07-28'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-02-01'


# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Under Review
# publication_short: Under Review

abstract: Hot fixes are urgent, unplanned changes deployed to production systems to address time-critical issues. Despite their importance, no existing evaluation benchmark focuses specifically on hot fixes. We present HotBugsjar, the first dataset dedicated to real-world hot fixes. From an initial mining of 10 active Apache projects totaling over 190K commits and 150K issue reports, we identified 746 software patches that met our hot-fix criteria. After manual evaluation, 679 were confirmed as genuine hot fixes, of which 110 are reproducible using a test suite. Building upon the Bugsjar framework, HotBugsjar integrates these 110 reproducible cases and makes available all 679 manually validated hot fixes, each enriched with comprehensive metadata to support future research. Each hot fix was systematically identified using Jira issue data, validated by independent reviewers, and packaged in a reproducible format with buggy and fixed versions, test suites, and metadata. HotBugsjar has already been adopted as the official challenge dataset for the Search-Based Software Engineering (SBSE) Conference Challenge Track, demonstrating its immediate impact. This benchmark enables the study and evaluation of tools for rapid debugging, automated repair, and production-grade resilience in modern software systems to drive research in this essential area forward.

tags:
  - Hot Fix
  - Software Maintenance
  - Benchmark

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  # ids:
  #   doi: 10.5555/123456

# Custom links
links:
  - type: paper
    label: Paper
    url: "https://dl.acm.org/doi/10.1145/3696630.3728564"
  - type: GitHub
    label: GitHub
    url: github.com/carolhanna01/HotBugs-dot-jar
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
